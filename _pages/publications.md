---
layout: page
permalink: /publications/
title: Publications
description: 
years-cj: [2021, 2020]
years-pp: [2020]
years-std: [2021, 2020]
nav: true
nav-order: a
---

## Conferences and journals
<div class="publications">

{% for y in page.years-cj %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

## Preprints
<div class="publications">

{% for y in page.years-pp %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f preprints -q @*[year={{y}}]* %}
{% endfor %}

</div>

## Standardization 
<div class="publications">

{% for y in page.years-std %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f standards -q @*[year={{y}}]* %}
{% endfor %}

</div>
