---
layout: page
title: Selamat Datang!
tagline: Online Market Place based Github Pages
---
{% include JB/setup %}

<div class="container">
  {% for post in site.posts %}
  <div class='posts'>
    <h1><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    <p>{{ content }}</p>
  {% endfor %}
  </div>
