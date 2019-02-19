---
layout: default
title:  "Blog"
---

# Recent Posts

{% for post in site.posts %}
 1. [{{post.title}}]({{post.url}})
{% endfor %}
