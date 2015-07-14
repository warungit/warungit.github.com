---
layout: page
title: Selamat Datang!
tagline: di Online Market Place based Github Pages
---
{% include JB/setup %}

<div class="container">
  {% for post in site.posts %}
  <div class='posts'>
    <h1><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h1>
    {{ post.content }}
	<a href="{{ BASE_PATH }}{{post.url}}">Lihat</a>
	<hr>
  {% endfor %}
  </div>
