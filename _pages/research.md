---
layout: page
permalink: /research/
title: Research
years: [2020, 2022]
pub: ["Conference Proceedings", "Abstracts and Presentations"]
nav: true
nav_order: 1
---
<!-- _pages/research.md -->
<div class="publications">

{% for p in page.pub %}
  <h4 class="publication">{{p}}</h4>
  {% bibliography -f papers -q @*[publication={{p}}]* %}
{% endfor %}

</div>
