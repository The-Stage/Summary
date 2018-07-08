---
layout: categories
title: Books
order: 4
---
{% if site.categories.stories == null %}
  <div class="row ">No post available.</div>
{% else %}
  {% for post in site.categories.stories %}
  <div class="row">
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </div>
  {% endfor %}
{% endif %}
