---
layout: default
title: Home
---


{% for post in site.posts %}
{% if post.single %}
<img src="{{ post.preview }}" data-action="zoom">
{% else %}
<a href="{{ post.url }}">
  <img src="{{ post.preview }}">
  <!-- {{ post.title }} -->
  </a>
<br />
{% endif %}
{% endfor %}
<br />