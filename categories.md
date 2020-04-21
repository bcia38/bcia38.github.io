---
layout: page
title: Categories
permalink: /categories/
---

{% for category_posts in site.categories %}
  <h2>#{{ category_posts[0] }}</h2>
  <ul>
    {% for post in category_posts[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
