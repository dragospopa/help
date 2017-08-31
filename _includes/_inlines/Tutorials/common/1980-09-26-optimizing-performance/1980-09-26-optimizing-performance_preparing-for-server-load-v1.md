<!-- usedin: [ _legacy_docker/Tutorials/1980-09-26-optimizing-performance-v1.md, _maestro/Tutorials/1980-09-26-optimizing-performance-v1.md, _node/tutorials/1980-09-26-optimizing-performance-v1.md, _rails/Tutorials/1980-09-26-optimizing-performance-v1.md] -->


## Preparing for server load

There are a number of steps you can take when expecting an increase in server load. It's always best to scale _before_ you need it - the relative cost for more servers for a few days is worth more than the potential lost traffic, and you can always scale down easily.

1.  [Add a load balancer to your stack](http://help.cloud66.com/web-server/load-balancing), and point your DNS to it. It will distribute traffic across your web servers, and offers benefits such as maximizing throughoutput, minimizing response times and avoiding overload on any single server.
2.  [Scale your application servers horizontally](http://help.cloud66.com/managing-your-stack/scaling) to the extent that you require.
3.  [Monitor your servers](http://help.cloud66.com/managing-your-stack/server-monitoring) to ensure that they are able to serve your users.