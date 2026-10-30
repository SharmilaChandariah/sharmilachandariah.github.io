---
title: "Recognition"
layout: page
permalink: /about/
---

# Recognition

{% if site.data.awards %}
<div class="section-card">
<h3>Awards &amp; Honors</h3>
<ul>
{% for award in site.data.awards %}
<li>{{ award.name }}</li>
{% endfor %}
</ul>
</div>
{% endif %}

<div class="section-card">
<h3>Certifications</h3>
<ul>
<li>Guidewire Certified ACE (expert-level Guidewire certification)</li>
</ul>
</div>

<div class="section-card">
<h3>Professional Memberships</h3>
<ul>
<li>Senior Member, IEEE</li>
<li>Member, IEEE Computer Society</li>
</ul>
</div>

<div class="section-card">
<h3>Experience</h3>
<ul>
<li><strong>2020&ndash;present:</strong> Senior Technical Lead, policy administration and enterprise generative AI, Fortune 500 property &amp; casualty insurance organization</li>
<li><strong>2016&ndash;2020:</strong> Senior Guidewire Developer, Personal Lines Transformation (Guidewire PolicyCenter), national U.S. insurer</li>
<li><strong>2011&ndash;2016:</strong> Senior Java Developer, multi-vendor ATM software modernization, global bank</li>
</ul>
</div>
