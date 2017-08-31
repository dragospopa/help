<!--  usedin: [ _legacy_docker/Tutorials/2017-02-26-ssl-certificate-issues-v1.md, _maestro/Tutorials/2017-02-26-ssl-certificate-issues-v1.md, _node/tutorials/2017-02-26-ssl-certificate-issues-v1.md, _rails/Tutorials/2017-02-26-ssl-certificate-issues-v1.md] -->


### Passphrase protected keys

You cannot use passphrase protected SSL certificate keys with Nginx. Using passphrase protected certificate keys will cause Nginx to prompt for the manual entry of passphrase at restart which will break the automatic deployment flow (and restart of Nginx after a server restart).

The symptoms of this is that your deployment gets stuck in the _Restarting Nginx_ step.

You can simply use a non-passphrase-protected version of your SSL certificate key when [adding an SSL key to your stack](/articles/ssl-certificate). Use the following command to do it (on your development computer):



{%include _inlines/Tutorials/common/2039-02-26-ssl-certificate-issues/code_2039-02-26-ssl-certificate-issues_passphrase-protected-v1.md  product = include.product %}




You will be prompted for your passphrase and the output will be generated after that.
