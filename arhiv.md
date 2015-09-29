---
layout: page
title: Архив
---

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &#8594; [ {{ post.title }} ]({{ post.url }})
{% endfor %}