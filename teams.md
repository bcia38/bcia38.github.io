---
title: Teams
permalink: /teams/
---

{% assign test = site.interclubs %}
<div>label:{{test.label}}</div>
<div>output:{{test.output}}</div>

{% assign teams = site.collections | where: "label", "interclubs" | first %}
<div>label:{{teams.label}}</div>
<div>output:{{teams.output}}</div>

Properties:
<ul>
{% for team in teams %}
  <li>{{ team }}</li>
{% endfor %}
</ul>

Files:
<ul>
{% for file in teams.files %}
  {% for x in file %}
    <li>{{ x }}</li>
  {% endfor %}
{% endfor %}
</ul>

Docs:
<ul>
{% for file in teams.docs %}
  {% for x in file %}
    <li>{{ x }}</li>
  {% endfor %}
{% endfor %}
</ul>