---
layout: default
permalink: /research/
title: Research
nav: true
nav_order: 2
---

<div class="post" style="margin-top: 3rem;">
  <div class="publications">
    
    <h3>Publications</h3>
    {% bibliography -q @*[category=published]* %}

    <h3>Working Papers</h3>
    {% bibliography -q @*[category=working]* %}

    <h3>Work in Progress</h3>
    <ol>
      <li>
        <strong>[Your Next Great Idea]</strong><br>
        <em>[A one-sentence description of the methodology or goal.]</em>
      </li>
    </ol>

  </div>
</div>
