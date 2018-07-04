---
layout: categories
title: Sport
order: 4
---
{% if site.categories.sport == null %}
  <div class="row ">No post available.</div>
{% else %}
  {% for post in site.categories.sport %}
  <div class="row">
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </div>
  {% endfor %}
{% endif %}
