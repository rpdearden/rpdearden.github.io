---
layout: page
title: Dead Fishes Blog
subtitle: A blog about Dead Fishes
---

![Me](/assets/img/DeadFishes.png)

Below are my blog posts.

<ul>
  {% for post in site.posts %}
    <li class="spaced">
      <a href="{{ post.url }}">{{ post.title }}</a> {{ post.date | date_to_long_string }}
    </li>
  {% endfor %}
</ul>
