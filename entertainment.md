---
layout: categories
title: Entertainment
order: 10
---
{% if site.categories.entertainment == null %}
  <div class="row ">No post available.</div>
{% else %}
  {% for post in site.categories.entertainment %}
  <div class="row">
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </div>
  {% endfor %}
{% endif %}
