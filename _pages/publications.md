---
layout: page
permalink: /publications/
title: Publications
description: Here is an almost-complete list of recent publications. Please find the list in PDF [here]. And you can also find my publications using this 
  ADS link or on my ORCID page.
years: [2009, 2013, 2014, 2016, 2017, 2018, 2019, 2020, 2021]
nav: false
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
