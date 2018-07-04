---
layout: categories
title: Fashion
order: 6
---
{% if site.categories.fashion == null %}
  <div class="row ">No post available.</div>
{% else %}
  {% for post in site.categories.fashion %}
  <div class="row">
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </div>
  {% endfor %}
{% endif %}
