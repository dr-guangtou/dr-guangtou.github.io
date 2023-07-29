---
sort_menu: 05
layout: page
permalink: /publications/
title: Publications
description: Song Huang's Publication List 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2014, 2013, 2009]
nav: true
---

- Here is an almost-complete list of recent publications. Please find my publication list in [PDF here](https://dr-guangtou.github.io/assets/pdf/pub.pdf) (Last update: 2022-09). And you can also find my publications using this [ADS link](https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0003-1385-7591&sort=date+desc) or on [my ORCID page](https://orcid.org/0000-0003-1385-7591).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
