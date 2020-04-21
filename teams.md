---
layout: page
title: Teams
permalink: /teams/
---

<ul>
{% for team in site.teams %}
  <li>{{ team.name }}</li>
{% endfor %}
</ul>