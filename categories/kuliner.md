---
layout: default
title: Kuliner
---

<h1>Kuliner</h1>

<ul>
{% for post in site.categories.Kuliner %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
