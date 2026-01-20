---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">



<h2>Preprints</h2>
{% bibliography --query @*[status=preprint] %}

<h2>Publications</h2>
{% bibliography --query @*[status=peerreviewed] %}





</div>
