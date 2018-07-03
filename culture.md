---
layout: categories
title: Culture
---

{% for post in site.posts %}
  {% if post.categories contains culture %}
  <div>
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </div>
  {% endif %}
{% endfor %}
