---
title: "Talks"
layout: page
permalink: /talks/
---

# Talks

{% assign conf = site.data.talks | where_exp: "t", "t.type != 'guest'" %}
{% assign guest = site.data.talks | where: "type", "guest" %}

{% if conf.size > 0 %}
<div class="section-card" markdown="0">
<h2>Conference Talks</h2>
<p>I speak on privacy-preserving AI, enterprise generative AI, and modernization in regulated industries.</p>
{% for talk in conf %}{% include talk.html talk=talk %}{% endfor %}
</div>
{% endif %}

{% if guest.size > 0 %}
<div class="section-card" markdown="0">
<h2>Guest Lectures</h2>
{% for talk in guest %}{% include talk.html talk=talk %}{% endfor %}
</div>
{% endif %}
