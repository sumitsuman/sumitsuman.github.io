---
layout: page
title: Blog
---

{% for post in site.posts %}
  * {{ post.date | date_to_string }}: [ {{ post.title }} ]({{ post.url }})
{{ post.excerpt }}
[Read more >>]({{ post.url }})
{% endfor %}