---
layout: categories
title: Politics
order: 5
---
{% if site.categories.politics == null %}
  <div class="row ">No post available.</div>
{% else %}
  {% for post in site.categories.politics %}
  <div class="row">
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </div>
  {% endfor %}
{% endif %}
