---
layout: page
title: politics
---

{% for post in site.categories.politics %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

