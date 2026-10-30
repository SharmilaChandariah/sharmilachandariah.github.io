---
title: "Publications"
layout: page
permalink: /publications/
---

# Publications

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, venue, or year...">

<div class="section-card" id="pubList">
<h2>Peer-Reviewed Publications</h2>

{% bibliography --query @*[keywords=peer] %}

<h2>Industry &amp; Trade Publications</h2>

{% bibliography --query @*[keywords=trade] %}

<h2>Articles &amp; Commentary</h2>

{% bibliography --query @*[keywords=writing] %}
</div>
