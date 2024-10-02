---
layout: page
permalink: /publications/
title: research
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->


{% include bib_search.liquid %}

### Active projects 

<div class="publications">
  {% bibliography --query @*[working=true]* %}
</div>  <br />

### Publications
<div class="publications">
  {% bibliography --query @*[working=false]* %}
</div>
