---
layout: responsive
title: Dev Blog
---

# Development Blog

This page is a little bugged due to the way Github generates pages.  I'm searching for a fix

----

{% for post in site.posts %}
### [{{post.title}}]({{ post.url }})



[Read More...]({{ post.url }})


{% endfor %}
