<!-- usedin: [ _legacy_docker/AddOns/haproxy-v1.md, _maestro/AddOns/haproxy-v1.md, _node/addons/haproxy-v1.md, _rails/AddOns/haproxy-v1.md] -->


## Configure HAProxy to use internal IPs

By default, HAProxy is configured to use the external IP address of your servers, but it can be changed to use the internal addresses if you have private networking enabled.

Simply replace any `server.ext_ipv4` values with `server.int_ipv4` using HAProxy CustomConfig (below).
