---
layout: categories
title: Lifestyle
order: 7
---
{% if site.categories.lifestyle == null %}
  <div class="row ">No post available.</div>
{% else %}
  {% for post in site.categories.lifestyle %}
  <div class="row">
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </div>
  {% endfor %}
{% endif %}
