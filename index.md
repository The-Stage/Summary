---
layout: index
title: The Stage
order: 1
---
{% assign p = (site.pages | sort: 'order') %}
{% for page in p %}
  <div>page.title : <a href="{{ page.url }}">link</a></div<
{% endfor %}
