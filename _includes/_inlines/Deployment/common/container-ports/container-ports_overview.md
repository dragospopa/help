<!-- post: -->


## Overview

Often times the purpose of a service inside your application is to respond to web queries from the internet. Actions like rendering and serving HTML pages or accepting HTTP POST actions are amongst the most common requirements from web services.

In a Cloud 66 for Docker stack, your services run inside containers. For this service to be available to anyone outside the container, we need to bridge it from inside to outside of the container.

This is not limited to HTTP or web traffic. The same concepts apply if your container serves non-HTTP traffic (like web sockets, DB containers or custom TCP / UDP traffic).



