<!-- usedin: [ _legacy_docker/AddOns/custom-web-servers-v1.md, _maestro/AddOns/custom-web-servers-v1.md, _node/addons/custom-web-servers-v1.md, _rails/AddOns/custom-web-servers-v1.md] -->


### Restart the web server

If supported by your web server, you can use the following command to restart the web server with no down time (this will send a USR2 signal to your webserver)



	sudo bluepill cloud66_web_server restart

