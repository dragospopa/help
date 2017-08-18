<!-- post: -->


### Important

Ensure that the certificate is valid: current date must be between the certificate’s start and end date. Certificate keys also should not be password protected




Through the [AWS ELB command line interface](http://aws.amazon.com/developertools/2536):

*   Run the command below to add a new SSL certificate:



{%include _inlines/Tutorials/common/1900-09-26-ssl-termination-on-load-balancers/code_1900-09-26-ssl-termination-on-load-balancers_important.md %}




*You should retrieve any available SSL certificate using this command:



{%include _inlines/Tutorials/common/1900-09-26-ssl-termination-on-load-balancers/code_1900-09-26-ssl-termination-on-load-balancers_important.md %}




*Run the command below to attach the SSL certificate to the load balancer:



{%include _inlines/Tutorials/common/1900-09-26-ssl-termination-on-load-balancers/code_1900-09-26-ssl-termination-on-load-balancers_important.md %}




*To delete a certificate, run the following command:



{%include _inlines/Tutorials/common/1900-09-26-ssl-termination-on-load-balancers/code_1900-09-26-ssl-termination-on-load-balancers_important.md %}




Refer to the [AWS documentation for more information](http://docs.aws.amazon.com/IAM/latest/UserGuide/InstallCert.html).
