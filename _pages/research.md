---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 2
---

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">

<h2>Working Papers</h2>
{% bibliography -q @*[category=working]* %}

<h2>Publications</h2>
{% bibliography -q @*[category=published]* %}

<h2>Work in Progress</h2>
<ul>
  <li>
    <strong>[Your Next Great Idea]</strong><br>
    <em>[A one-sentence description of the methodology or goal.]</em>
  </li>
  <li>
    <strong>[Your Next Great Idea]</strong><br>
    <em>[A one-sentence description of the methodology or goal.]</em>
  </li>
</ul>

</div>
