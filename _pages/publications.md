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


### Publications
<div class="publications">
  {% bibliography --query @*[working=false]* %}
</div>

### Selected works in progress

<div class="publications">
  {% bibliography --query @*[working=true]* %}
</div>  <br />