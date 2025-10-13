---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<!-- {% include bib_search.liquid %} -->

<div class="publications">

  <h2>Peer-Reviewed Publications</h2>
  {% bibliography -f papers %}

  <h2>Thesis</h2>
  {% bibliography -f thesis %}

</div>