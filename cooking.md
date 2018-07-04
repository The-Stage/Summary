---
layout: categories
title: Cooking
order: 11
---
{% if site.categories.cooking == null %}
  <div class="row ">No post available.</div>
{% else %}
  {% for post in site.categories.cooking %}
  <div class="row">
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </div>
  {% endfor %}
{% endif %}
