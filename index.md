---
layout: home
---

You can also find the source code to this blog on my [GitHub](https://github.com/SitrusKettu/sitruskettu.dev).

<ul>
  {% for post in site.posts %}
    <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
    <i>{{ post.date | date_to_long_string: "ordinal", "US" }}</i>
    <p>{{ post.excerpt }}</p>
  {% endfor %}
</ul>
