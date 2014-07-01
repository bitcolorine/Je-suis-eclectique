---
layout: default
title: Home
---

A compendium of artists.

Or scribblers.

And a blog:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
