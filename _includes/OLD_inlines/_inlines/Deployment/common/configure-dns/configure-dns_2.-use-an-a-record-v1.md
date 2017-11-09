


### 2. Use an A record

This involves using an A record to point your root domain at your load balancer and then redirecting traffic to www in Nginx.

1.  Create a CNAME record for www pointing at the Cloud 66 hostname on your load balancer.
2.  Create an A record for your root domain (eg. example.com) pointing at your load balancer IP address.
3.  ​Use [network redirects]({% if include.product == "skycap" %}https://help.cloud66.works/maestro/stack-management/network-configuration.html{% else %}https://help.cloud66.works/{{ include.product }}/stack-management/network-configuration.html{% endif %}) to permanently redirect all traffic from example.com to www.example.com.