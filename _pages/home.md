---
title: "Home"
layout: homelay
permalink: /
---

<h1 class="home-hero">{{ site.name }}</h1>

## Hi, I'm Sharmila!

I am a technology leader and independent researcher in insurance and financial services technology, specializing in enterprise generative AI and data privacy. My work focuses on designing privacy-preserving data and AI systems for regulated industries: architectures that let organizations adopt generative AI without exposing sensitive customer data to the model.

My central contribution is **"reasoning without seeing"**, a schema-only approach to text-to-SQL in which the AI model generates queries from the database structure alone and never sees the underlying data. The queries run inside the enterprise's own database, and results go directly to the user. I took this system from concept to production at a top-100 insurer. There it passed full enterprise AI governance review and was adopted by more than 150 teams across policy, claims, underwriting, and testing, with 95% query accuracy and 90% of data requests moved to self-service. The approach is domain-agnostic and applies to any regulated industry, including banking and healthcare.

Over 15 years, I have led modernization programs across banking and insurance, from ATM software modernization for a global bank to Guidewire PolicyCenter transformations for major U.S. insurers. I am a Senior Member of IEEE and a Guidewire Certified ACE, and I serve on the advisory board of an insurance technology startup. My writing appears in Claims Journal and PropertyCasualty360, and I speak on privacy-preserving AI at IEEE conferences.

{% capture selected %}{% bibliography --query @*[selected=true] %}{% endcapture %}
{% if selected contains "pub-entry" %}
## Selected publications

<div class="section-card selected-pubs" markdown="0">
{{ selected }}
<p style="margin: var(--space-4) 0 0;"><a href="{{ '/publications' | relative_url }}">All publications &rarr;</a></p>
</div>
{% endif %}
