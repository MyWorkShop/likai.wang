---
layout: default
title: Home
---

# Likai Wang

{% for project in site.projects %}
{% if project.single %}
<img src="{{ project.preview }}" data-action="zoom">
{% else %}
<a href="{{ project.url }}"><img src="{{ project.preview }}"></a>
<br />
{% endif %}
{% endfor %}