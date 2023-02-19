---
layout: post
title: "Index"
---

<ul>
  {% for post in site.posts %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <h3>{{ post.date }}</h3>
    <h3>{{ post.excerpt }}</h3>
  {% endfor %}
</ul>
