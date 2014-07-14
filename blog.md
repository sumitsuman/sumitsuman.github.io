---
layout: page
title: Blog
---

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.excerpt }} ]({{ post.url }})
{% endfor %}