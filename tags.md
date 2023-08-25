---
layout: default
title: Tags
permalink: /tags/
---

# Tags

{% for tag in site.tags %}
  - [{{ tag[0] }}]({{ site.url }}/tags/{{ tag[0] }})
{% endfor %}