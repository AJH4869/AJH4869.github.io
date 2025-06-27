---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<div class="publications">

<h3>Journal & Conference Papers</h3>
{% bibliography  --file pub.bib %}

<h3>Preprints</h3>
{% bibliography  --file preprint.bib %}

</div>

