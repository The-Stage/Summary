---
layout: categories
title: Technology
order: 9
---
{% if site.categories.technology == null %}
  <div class="row ">No post available.</div>
{% else %}
  {% for post in site.categories.technology %}
  <div class="row">
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </div>
  {% endfor %}
{% endif %}
