---
layout: project
title: "Nothing Was Inconsistent. Everything Was."
date: 1999-05-02 00:00:00
project-date: "2014 – 2018"
description: "Vyond's animation tool had grown fast—too fast. Beta testing exposed a product that worked feature by feature, but fell apart in practice. A single interaction pattern changed that."
teaser-image: /assets/img/ga/teaser.png
screens: /assets/img/ga/screens.png
tags: [Information architecture, Interaction design, User research]
---

<!-- Hero Section -->
<div class="full-width-section" style="background-color: #EDEFF2;">
  <div class="container">
    <div class="d-flex justify-content-between align-items-baseline project-lang-row">
      <h1>{{ page.title }}</h1>
      <a href="/projects/ga-ja.html" class="lang-switch-link">日本語</a>
    </div>
    <p class="lead" style="max-width: 640px;">{{ page.description }}</p>
    <div class="py-4">
      <div style="background-color: #9BDEA8; border-radius: 8px; padding: 2rem;">
        <!-- Device frame -->
        <div style="background: #1c1c1e; border-radius: 10px; padding: 14px 14px 28px 14px; position: relative; box-shadow: 0 2px 12px rgba(0,0,0,0.3);">
          <div style="width: 6px; height: 6px; background: #3a3a3a; border-radius: 50%; margin: 0 auto 10px;"></div>
          <video class="img-fluid" autoplay muted loop playsinline style="border-radius: 4px; display: block;">
            <source src="/assets/img/ga/color-demo.mp4" type="video/mp4">
          </video>
        </div>
      </div>
    </div>
    <hr class="project-meta-rule">
    <div class="project-meta-grid">
      <div>
        <div class="meta-label">Role</div>
        <p class="meta-value">Senior UX Designer</p>
      </div>
      <div>
        <div class="meta-label">Team</div>
        <p class="meta-value">Design, Engineering, Product</p>
      </div>
    </div>
  </div>
</div>

<!-- Context -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">Context</h3>
    <p>I joined Vyond in 2014 — three designers, ~30 employees, working across Hong Kong, Taiwan, and San Francisco. Over four years, headcount doubled annually. I grew with the company, helping build the design processes and patterns that scaling required.</p>
    <p>The app was being rebuilt from the ground up — not migrated, but redesigned entirely. To move fast, the design team split into smaller groups, each owning a set of features. It worked, until it didn't. With no shared oversight, every team made sensible local decisions that added up to a product without a common language. Private beta testing with new users and power users made that undeniable.</p>
    <p>The product was a browser-based animation tool that let non-designers make professional video — trusted by many Fortune 500 companies. Here's a sense of its scope:</p>
    <div class="mt-4" style="border: 1px solid #e0e0e0; border-radius: 8px; padding: 1rem 1.25rem;">
      <div class="row mb-2">
        <div class="col-6 col-md-3 mb-3">
          <p class="card-tags mb-1">Scene</p>
          <p style="font-size: var(--text-sm); opacity: 0.7; line-height: 1.6;">Background · Camera · Duration · Transitions</p>
        </div>
        <div class="col-6 col-md-3 mb-3">
          <p class="card-tags mb-1">Characters</p>
          <p style="font-size: var(--text-sm); opacity: 0.7; line-height: 1.6;">Actions · Expressions · Lip sync · Audio</p>
        </div>
        <div class="col-6 col-md-3 mb-3">
          <p class="card-tags mb-1">Effects</p>
          <p style="font-size: var(--text-sm); opacity: 0.7; line-height: 1.6;">Group · Motion· Masking · Filters</p>
        </div>
        <div class="col-6 col-md-3 mb-3">
          <p class="card-tags mb-1">Assets & Output</p>
          <p style="font-size: var(--text-sm); opacity: 0.7; line-height: 1.6;">Props · Text · Audio · Templates ·　Themes</p>
        </div>
      </div>
      <details style="border-top: 1px solid #e0e0e0; padding-top: 1rem;">
        <summary style="cursor: pointer; font-size: var(--text-sm); color: var(--text-muted, #666); user-select: none;">See the full map →</summary>
        <img src="/assets/img/ga/structure.png" class="rounded mt-3" style="max-width: 60%; display: block; margin: 0 auto;" alt="Full structure of a Vyond video">
        <p class="figure-caption text-center mt-2">Every node a feature, every feature its own interaction pattern</p>
      </details>
    </div>

  </div>
</div>

<!-- People -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">The people</h3>
    <p>As the rebuilt app approached beta release, testing exposed two distinct failure modes — one for new users, one for experienced ones.</p>
    <div class="row mt-4 mb-2">
      <div class="col-sm-6 mb-4">
        <div class="persona-card persona-card--newbie">
          <div class="d-flex align-items-start gap-3 mb-3">
            <img src="/assets/img/ga/persona-newbie.png" class="persona-avatar" alt="Newbie">
            <div class="speech-bubble flex-grow-1">"It was a little bit confusing at times... maybe can do it another time and get the gist of it."</div>
          </div>
          <p class="persona-type">Newbie</p>
          <p class="persona-body">Just signed up on a trial account. Wants to make one video — just one. Too many options with no clear entry point, and it's easy to feel lost before they've even started.</p>
        </div>
      </div>
      <div class="col-sm-6 mb-4">
        <div class="persona-card persona-card--poweruser">
          <div class="d-flex align-items-start gap-3 mb-3">
            <img src="/assets/img/ga/persona-champion.png" class="persona-avatar" alt="Product Champion">
            <div class="speech-bubble flex-grow-1">"The interface is quite different from legacy... I'm trying to make the character talk, but I'm not sure where to click."</div>
          </div>
          <p class="persona-type">Power User</p>
          <p class="persona-body">Heavy user making videos at scale, often for a whole team. Knows what they want — the tool just needs to get out of the way. Inconsistent patterns mean relearning interactions across every panel.</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Problem -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">The problem</h3>
    <p>Testing surfaced consistent patterns of confusion across the product. Some of what we found:</p>
    <img src="/assets/img/ga/panel-before.png" class="img-fluid rounded mt-3" alt="Asset panel before redesign">
  </div>
</div>

<!-- Goals -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">Goals</h3>
    <p>The redesign had to work for two very different people — someone opening the app for the first time, and someone who'd used it for years. The solution had to serve both without compromise.</p>
    <ol>
      <li><strong>Discoverability for beginners</strong> — easy to explore and complete a short video with confidence</li>
      <li><strong>Speed for power users</strong> — experienced creators know what they want; the tool should get out of the way</li>
    </ol>
  </div>
</div>

<!-- Approach -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">Approach</h3>
    <p>The same underlying flow — <em>browse → select → apply → customise</em> — applied across every asset type in the product. The solution was a progressive disclosure pattern we called the <strong>Toolbox</strong>, applied consistently across all of them:</p>
    <ul>
      <li><strong>Quick access</strong> — bookmarked items, surfaced immediately</li>
      <li><strong>Recently used</strong> — the shortcut for repeat tasks</li>
      <li><strong>Categories</strong> — structured browsing for discovery</li>
      <li><strong>Custom</strong> — brand assets or uploaded content</li>
    </ul>
    <p>A beginner uses Categories to explore. A power user lives in Recently Used. An enterprise team uses Custom to enforce brand consistency. One pattern, three mental models.</p>
  </div>
</div>

<!-- Final design -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">The result</h3>
    <img src="/assets/img/ga/solution.png" class="img-fluid rounded mb-4" alt="Final asset panel design">
    <p class="figure-caption text-center mb-4">The Toolbox pattern applied across characters, categories, text, and audio panels</p>
    <p>What changed wasn't just the UI — it was the expectation: users now knew what to do when they encountered any new part of the tool, because they'd already learned the pattern somewhere else.</p>
  </div>
</div>

<!-- Outcome -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">Outcome</h3>
    <div class="row mb-4">
      <div class="col-md-4 mb-4">
        <p class="persona-type">For new users</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">Could navigate any panel without a tutorial — the pattern transferred.</p>
      </div>
      <div class="col-md-4 mb-4">
        <p class="persona-type">For power users</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">Consistent patterns eliminated the relearning tax. Quick access and recents gave experienced creators the speed they needed.</p>
      </div>
      <div class="col-md-4 mb-4">
        <p class="persona-type">For the team</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">New features could be built to a shared pattern — reducing design and engineering overhead on each subsequent release. The Toolbox is still in use years after I left.</p>
      </div>
    </div>
    <p style="font-size: var(--text-sm); line-height: 1.7; opacity: 0.65;">The problem wasn't bad design — it was no shared design. When teams move fast in parallel, each decision makes local sense. The cost accumulates invisibly until someone does the test that makes it undeniable.</p>
  </div>
</div>
