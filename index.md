---
layout: index
title: The Stage
order: 1
---
{% for page in site.pages %}
  <div>page.title : <a href="{{ page.url }}">link</a></div<
{% endfor %}
