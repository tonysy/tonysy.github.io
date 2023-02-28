---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order. Full list can be found at <b><a href='https://scholar.google.com/citations?user=8XQPi7YAAAAJ&hl=en'>Google Scholar</a></b>.
years: [2023, 2022, 2021, 2020, 2019, 2017]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
