---
layout: page
title: Selamat Datang!
tagline: di Online Market Place based Github Pages
---
{% include JB/setup %}

<div style='background:#ffffff;color:black;border:1px solid #ffffff;border-radius:5px;padding:3px;text-align:center;'>
Cek cara Posting <a href='https://warungit.github.io/new-page.html'>Disini</a> Terima Kasih :)
</div>

<div class="container">
  {% for post in site.posts %}
  <div class='posts'>
    <h1><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h1>
    {{ post.content }}
	<a href="{{ BASE_PATH }}{{post.url}}" class='tombol'>Lihat</a>
	<hr>
  {% endfor %}
  </div>
