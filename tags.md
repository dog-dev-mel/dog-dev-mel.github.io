---
layout: tags
title: Tags
permalink: /tags/
---

# Tags

{% for tag in site.tags %}
## {{ tag[0] }} ({{ tag[1].size }})

{% for post in tag[1] %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}

{% endfor %}