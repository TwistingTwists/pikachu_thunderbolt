---
layout: default
title: Blog
---

### Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url | prepend:"/pikachu_thunderbolt" }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
