---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<!-- <div class="publications"> -->
<!-- 
{% bibliography -f {{ site.scholar.bibliography }} %}

<!-- </div> -->
<div class="publications">

<h1>health information accessibility</h1>

{% bibliography -f {{ site.scholar.bibliography.papers_clinical }} %}

<!-- <h1>clinical applications</h1>

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers_clinical -q @*[year={{y}}]* %}
{% endfor %} -->

</div>
