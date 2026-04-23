---
layout: page
title: "บทความด้านเทคโนโลยี"
permalink: /blog/technology/
---

{% for post in site.categories.Technology %}
  - [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%-d %b %Y" }})
{% endfor %}