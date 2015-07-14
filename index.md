---
layout: page
title: Selamat Datang!
tagline: Online Market Place based Github Pages
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    <li>{{ content }}
  {% endfor %}
</ul>
