---
layout: page
permalink: /research/
title: Research
years: [2020, 2022]
pub: ["Conference Proceedings", "Workshops","Abstracts and Presentations"]
nav: true
nav_order: 1
---
<!-- _pages/research.md -->
<div class="publications">

{% for y in page.year %}
  <h4 class="year">{{y}}</h4>
  {% bibliography -f papers -q @*[publication={{y}}]* %}
{% endfor %}

</div>
