---
layout: page
title: "Interclubs"
permalink: "/interclubs/"
---

<ul>
  {% for team in site.interclubs %}
    <li>
      <a href="{{ team.url }}">{{ team.name }}</a>
    </li>
  {% endfor %}
</ul>