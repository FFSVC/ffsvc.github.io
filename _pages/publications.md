---
layout: page
permalink: /publications/
title: Publications
description:
years: [2022,2020]
types: ["System Description 2020"]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

<div class="publications">
{% for y in page.types %}
  <h2 class="type">{{y}}</h2>
  {% bibliography -f papers -q @*[type={{y}}]* %}
{% endfor %}

</div>
