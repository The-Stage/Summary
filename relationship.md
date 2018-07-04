---
layout: categories
title: Relationship
order: 8
---
{% if site.categories.relationship == null %}
  <div class="row ">No post available.</div>
{% else %}
  {% for post in site.categories.relationship %}
  <div class="row">
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </div>
  {% endfor %}
{% endif %}
