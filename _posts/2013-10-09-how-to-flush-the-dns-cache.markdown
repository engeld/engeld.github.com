---
layout: post
title: "How to flush the DNS Cache on Mac OSX"
---
Because otherwise I always have to search it again:

{% highlight bash %}
$ sudo killall -HUP mDNSResponder
{% endhighlight %}

This command will reset (flush) the DNS cache.  

*Source: [Apple Support](http://support.apple.com/kb/HT5343)*
