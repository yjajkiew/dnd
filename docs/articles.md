---
layout: default
title: Articles
nav_order: 1
comments: true
---

# Liste des articles

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%Y-%m-%d" }} : <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
