---
layout: categories
title: Culture
---

{% for post in site.posts %}
  <div>
    <a href="{{ post.url | where_exp: "categories", "post.categories contains 'culture'" }}">
      {{ post.title | where_exp: "categories", "post.categories contains 'culture'" }}
    </a>
  </div>
{% endfor %}
