---
layout: default
title: Home
---

# Welcome to My Blog

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
