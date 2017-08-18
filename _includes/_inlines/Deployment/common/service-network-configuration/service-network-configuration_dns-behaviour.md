<!-- post: -->


### DNS Behaviour

The `dns_behaviour` directive allows you to change the default behaviour of returned DNS addresses of different versions. As outlined above, ElasticDNS always try to return the version of the container that has the same version of the caller. You can change this behaviour by setting `dns_behaviour` value to `non-versioned`, in which case ElasticDNS will return the address of containers with latest version.
