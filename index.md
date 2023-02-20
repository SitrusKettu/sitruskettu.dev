---
layout: home
---

<ul>
  {% for post in site.posts %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>Posted: {{ post.date }}</p>
    <h3>{{ post.excerpt }}</h3>
  {% endfor %}
</ul>
