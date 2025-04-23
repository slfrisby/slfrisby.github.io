---
layout: page
permalink: /publications/
title: publications
description: 
years: [preprints, 2025, 2023]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

<div class="publications">

{%- for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
