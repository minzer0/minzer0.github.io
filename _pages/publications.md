---
layout: page
permalink: /publications/
title: publications
description: Peer-reviewed publications in reverse chronological order, followed by my master's thesis.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography-section">Peer-reviewed publications</h2>

{% bibliography --file papers %}

<h2 class="bibliography-section">Thesis</h2>

{% bibliography --file thesis %}

</div>
