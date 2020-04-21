---
layout: page
title: Sponsors
permalink: /sponsors/
---

<ul>
{% for sponsor in site.data.sponsors %}
  <li>{{ sponsor.name }}: {{ sponsor.url }}</li>
{% endfor %}
</ul>