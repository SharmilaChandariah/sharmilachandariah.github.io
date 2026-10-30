---
title: "Research"
layout: page
permalink: /research/
---

# Research &amp; Original Contributions

My work sits where **regulated-industry data** meets **enterprise generative AI**: how to give people the power of AI over sensitive data without handing that data to the model.

<div class="research-grid">

<div class="research-card">
<img src="{{ '/images/research/reasoning-without-seeing.svg' | relative_url }}" class="research-thumb" width="400" height="200" alt="Schema-only architecture: the model sees the schema, never the data">
<div class="research-body">
<h2 class="research-title">Reasoning Without Seeing: Privacy-Preserving Text-to-SQL</h2>
<p class="research-desc">A schema-only architecture in which a language model writes SQL from table and column definitions alone and never sees a single customer record. The query executes inside the enterprise database and results go straight to the authorized user, so sensitive data never crosses the AI boundary. The design evolved from a pure schema-passing model to retrieval-augmented generation (RAG) over large schemas, and now to a Model Context Protocol (MCP) architecture. Deployed at a Fortune 500 P&amp;C insurance organization after full AI governance certification: <strong>150+ teams</strong> adopted it, with <strong>95% accuracy</strong> and <strong>90% of data requests moved to self-service</strong>.</p>
<div class="pub-actions">
<a href="https://github.com/SharmilaChandariah/SchemaAware-NL2SQL" target="_blank" class="btn-pill btn-git">Code</a>
<a href="https://medium.com/@sharmiladevic/the-silent-revolution-how-gen-ai-text-to-sql-ai-is-changing-the-game-4ea49afa1a4b" target="_blank" class="btn-pill btn-link">Article</a>
<a href="{{ '/talks' | relative_url }}" class="btn-pill btn-slides">Talks</a>
</div>
</div>
</div>

<div class="research-card">
<img src="{{ '/images/research/transient-schema.svg' | relative_url }}" class="research-thumb" width="400" height="200" alt="Legacy data flowing directly to a modern policy system through a transient layer">
<div class="research-body">
<h2 class="research-title">Transient Schema for Legacy Policy Migration</h2>
<p class="research-desc">Policy migrations normally require every legacy record to be persisted in staging tables before it can be loaded, and some legacy data cannot be staged at all. I designed a <em>transient entity</em> approach that carries legacy data through the migration pipeline in memory, without staging, so any legacy policy data can now be migrated into Guidewire PolicyCenter. The solution was adopted by the migration program and earned a Star Associate Award.</p>
</div>
</div>

<div class="research-card">
<img src="{{ '/images/research/regulated-genai.svg' | relative_url }}" class="research-thumb" width="400" height="200" alt="Generative AI inside a regulated-industry boundary">
<div class="research-body">
<h2 class="research-title">Enterprise Generative AI for Regulated Workflows</h2>
<p class="research-desc">Applying generative AI to insurance and banking operations under real governance constraints: an underwriting-support solution that cut underwriter research time by more than 90%, retrieval-based document search over policy and procedure content, and domain-aware production monitoring for policy administration systems. The common thread is AI that fits the controls regulated industries already have, rather than asking them to relax those controls.</p>
<div class="pub-actions">
<a href="https://github.com/SharmilaChandariah/DocSearchPOCCode" target="_blank" class="btn-pill btn-git">Code</a>
</div>
</div>
</div>

<div class="research-card">
<img src="{{ '/images/research/pas-modernization.svg' | relative_url }}" class="research-thumb" width="400" height="200" alt="Legacy core systems modernized into a platform">
<div class="research-body">
<h2 class="research-title">Core System Modernization in Banking &amp; Insurance</h2>
<p class="research-desc">Fifteen years of hands-on modernization: multi-vendor ATM software for a global bank, Guidewire PolicyCenter personal-lines transformation for a national insurer, and policy administration system modernization for a Fortune 500 P&amp;C carrier. I write about what these programs teach, from PAS migration best practices to automating policy-change workflows.</p>
<div class="pub-actions">
<a href="https://www.propertycasualty360.com/2024/07/22/best-practices-in-pc-policy-administration-system-modernization/" target="_blank" class="btn-pill btn-link">Article</a>
</div>
</div>
</div>

</div>
