---
layout: project
title: "End-to-End Journey Mapping"
company: Flow
featured: true
order: 3
project-date: "2025"
description: "Surfacing the systemic gaps blocking automation and self-service growth through stakeholder interviews and journey mapping."
teaser-image: assets/img/flow/dashboard.png
tags: [Journey Mapping, Stakeholder Research, Strategy]
---

<!-- Hero Section -->
<div class="full-width-section" style="background-color: #EDEFF2;">
  <div class="container">
    <div class="d-flex justify-content-between align-items-baseline project-lang-row">
      <h1>{{ page.title }}</h1>
      <a href="/projects/retail-ja.html" class="lang-switch-link">日本語版</a>
    </div>
    <p class="lead" style="max-width: 640px;">{{ page.description }}</p>
    <div class="py-4">
      <img src="/assets/img/flow/dashboard.png" class="img-fluid rounded" alt="Flow analytics dashboard">
    </div>
    <hr class="project-meta-rule">
    <div class="project-meta-grid">
      <div>
        <div class="meta-label">Role</div>
        <p class="meta-value">UX Designer (Lead)</p>
      </div>
      <div>
        <div class="meta-label">Team</div>
        <p class="meta-value">Sales, Operations, Engineering, Management</p>
      </div>
      <div>
        <div class="meta-label">Timeline</div>
        <p class="meta-value">4–5 weeks</p>
      </div>
      <div>
        <div class="meta-label">Skills</div>
        <p class="meta-value meta-skills">Journey mapping · Stakeholder research · Systems thinking · Strategic prioritisation</p>
      </div>
    </div>
  </div>
</div>

<!-- Context -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">Context</h3>
    <p>Flow is a B2B retail analytics platform for Japanese SMB retailers — helping store managers understand store performance: store traffic, sales, conversion, and cross-store comparison. The business was shifting from hardware-dependent revenue toward SaaS platform revenue, which meant onboarding needed to scale.</p>
    <p>The problem: onboarding had been built for a hardware-first world. It required physical installations, manual configurations, and coordination across sales, operations, and engineering — with each team only knowing their own slice of the process. The business wanted to move faster. But no one had ever looked at the whole thing.</p>
  </div>
</div>

<!-- Problem -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">The Problem</h3>
    <p>Because each team only saw their part, no one could answer a simple question: <em>where is onboarding actually breaking down?</em></p>
    <p>The symptoms were clear — long lead times before clients could go live, high-touch manual work at every stage, delays cascading from one team to the next. But without a shared view of the journey, fixing it meant guessing.</p>
    <p>Critical information was being collected ad hoc throughout: billing details in spreadsheets and emails, client requirements gathered informally, handoffs between teams undocumented. It wasn't any single team's fault — it was a systemic gap nobody had been asked to own.</p>
  </div>
</div>

<!-- Approach -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">Approach</h3>
    <p>I owned this end-to-end. I interviewed all four stakeholders individually — sales, operations, engineering, and management — not to gather opinions, but to map what was actually happening. From those conversations I built an initial journey map, then brought the group together in a single session to verify, challenge, and extend it collectively.</p>
    <p>That session is where alignment happened. With everyone in the room seeing the same picture for the first time, gaps and dependencies that had never been made explicit became visible. I took the consolidated findings away, finalised the map, and reshared with the team.</p>
    <p>The priority order largely determined itself — the dependencies between problems meant there wasn't much room to resequence. Data foundations had to come first, because without trustworthy data, self-service features would be built on shaky ground.</p>
    <div class="py-4">
      <img src="/assets/img/flow/journeymap.png" class="img-fluid rounded" alt="Client onboarding journey map">
      <p class="figure-caption text-center mt-2">End-to-end journey showing touchpoints, ownership, and gaps across all three teams</p>
    </div>
  </div>
</div>

<!-- Findings -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">What We Found</h3>
    <p>Three recurring themes emerged across every team's account of the process:</p>
    <div class="row mt-4">
      <div class="col-md-4 mb-4">
        <p class="persona-type">Data foundations</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">Basic data quality issues were eroding client trust before onboarding was even complete. Missing fields (postal code), inconsistent address structures, and unmanaged accuracy expectations meant clients questioned the platform before they'd had a chance to use it.</p>
      </div>
      <div class="col-md-4 mb-4">
        <p class="persona-type">Operational bottlenecks</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">Demo and production tenant creation, store additions, user imports — all done manually by the operations team. Every new client was a bespoke project. There was no path to self-service, and no capacity to scale without hiring.</p>
      </div>
      <div class="col-md-4 mb-4">
        <p class="persona-type">Process gaps</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">Billing was collected late — sometimes not until clients complained. POS integration types and formats were not tracked systematically, making it impossible to automate compatibility checks. Domain whitelisting and brand setup were ad hoc.</p>
      </div>
    </div>
  </div>
</div>

<!-- Priorities -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">Priorities</h3>
    <p>Using a structured opportunities framework — mapping business outcomes, product outcomes, objectives, and key results against candidate solutions — the team aligned on a priority order across three tiers.</p>
    <div class="py-4">
      <img src="/assets/img/flow/opportunities-map.png" class="img-fluid rounded" alt="Opportunities map showing prioritised recommendations">
      <p class="figure-caption text-center mt-2">Opportunities mapped against business and product outcomes to determine what to tackle first</p>
    </div>
    <div class="row mt-2">
      <div class="col-md-4 mb-4">
        <p class="persona-type">1. Fix data foundations</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">Without trustworthy data, nothing else mattered. First priority was resolving the issues that were actively breaking client confidence: adding missing fields, fixing address structure, and creating a clear process for communicating accuracy expectations.</p>
      </div>
      <div class="col-md-4 mb-4">
        <p class="persona-type">2. Enable self-service</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">The biggest constraint on growth was operations bandwidth. Second priority was removing manual steps from the critical path: self-service store addition, bulk user and store import, and simplified demo/production account creation.</p>
      </div>
      <div class="col-md-4 mb-4">
        <p class="persona-type">3. Strategic improvements</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">Longer-horizon fixes that would unlock the next stage of scale: moving billing earlier in the process, tracking POS integrations systematically, and enabling brand and domain whitelisting for enterprise clients.</p>
      </div>
    </div>
    <p class="mt-2">For the first time, all four stakeholders shared a single view of the onboarding journey. The map gave the organisation a common language for a process that had previously existed only in separate people's heads — and the dependency structure made the priority order clear once everyone could see the whole picture.</p>
  </div>
</div>
