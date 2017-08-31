<!--  usedin: [ _legacy_docker/deployment/deployment-gateway-v1.md, _maestro/Deployment/deployment-gateway-v1.md, _node/deployment/deployment-gateway-v1.md, _rails/deployment/deployment-gateway-v1.md, _skycap/deployment/deployment-gateway-v1.md] -->


## How to deploy your stack behind the gateway server

Gateway management is available through [toolbelt](/toolbelt/toolbelt-gateway-management) .

First you need to define a gateway:



```
$ cx gateways add --name aws_bastion --address 1.1.1.1  --username ec2-user  --private-ip 2.2.2.2
```



In order to use this gateway for a stack deployment, you need to first specify it in the manifest:



```
production:
   	gateway:
   	    name: aws_bastion
   	    username: ec2-user
```



and then make it available before you start the deployment:



```
$ cx gateways open --name aws_bastion --key /tmp/gateway.pem --ttl 1h
```



Now you can start deploying your stack.

After the deployment is finished you can invalidate the gateway or leave it until the TTL is over.



{%include _inlines/Deployment/common/deployment-gateway/code_deployment-gateway_how-to-deploy-your-stack-behind-the-v1.md  product = include.product %}



