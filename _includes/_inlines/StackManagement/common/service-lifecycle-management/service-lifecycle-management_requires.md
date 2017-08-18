<!-- post: -->


### Requires

In some cases, you may want to make sure that a service is only started if another service is started. The `requires` option allows you to set such dependencies. For example:

{% highlight yaml %}
services:
    &#60;service_name&#62;:
        image: cloud66/sample
        requires:
          - "my_api"    
{% endhighlight %}

* * *
