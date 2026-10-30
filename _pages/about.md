---
title: "Recognition"
layout: page
permalink: /about/
---

# Recognition

<div class="section-card">
<div class="pi-card">
<img src="{{ site.photo | prepend: '/images/' | relative_url }}" class="pi-photo" alt="{{ site.name }}" width="160" height="160">
<div>
<h2 class="pi-name">{{ site.name }}</h2>
<p style="font-style: italic; color: var(--text-secondary);">{{ site.title }} &middot; {{ site.institution }}</p>
<p>Designing privacy-preserving data and AI systems for regulated industries. 15+ years across banking and insurance technology.</p>
<div class="pi-links">
{% if site.email %}<a href="mailto:{{ site.email }}" class="icon-link" title="Email" aria-label="Email">{% include icon.html name="envelope" %}</a>{% endif %}
{% if site.links.github and site.links.github != "" %}<a href="{{ site.links.github }}" class="icon-link" title="GitHub" aria-label="GitHub">{% include icon.html name="github" %}</a>{% endif %}
{% if site.links.orcid and site.links.orcid != "" %}<a href="{{ site.links.orcid }}" class="icon-link" title="ORCID" aria-label="ORCID">{% include icon.html name="orcid" %}</a>{% endif %}
{% if site.links.linkedin and site.links.linkedin != "" %}<a href="{{ site.links.linkedin }}" class="icon-link" title="LinkedIn" aria-label="LinkedIn">{% include icon.html name="linkedin" %}</a>{% endif %}
</div>
</div>
</div>
</div>

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
