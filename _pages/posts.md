---
layout: default
title: Posts
permalink: /posts/
---

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}