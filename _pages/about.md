---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  .page__title { display: none; }
  .page__content { max-width: 34em; }
  .home-intro p { margin-bottom: 1em; }
  .home-section {
    margin: 2em 0 1em 0;
    padding-bottom: 0.3em;
    border-bottom: 1px solid #e0e3e5;
    font-size: 1.2em;
    font-weight: 700;
    letter-spacing: 0.02em;
    color: #2f3538;
  }
  .edu {
    display: grid;
    grid-template-columns: 1fr auto;
    column-gap: 1.5em;
    row-gap: 0.2em;
    line-height: 1.5;
  }
  .edu-school {
    grid-column: 1 / -1;
    margin-top: 0.8em;
    font-weight: 500;
    color: #2f3538;
  }
  .edu-school:first-child { margin-top: 0; }
  .edu-degree { padding-left: 1em; }
  .edu-year {
    white-space: nowrap;
    color: #6f777d;
    font-variant-numeric: tabular-nums;
  }
  @media (max-width: 600px) {
    .edu { grid-template-columns: 1fr; row-gap: 0; }
    .edu-year { padding-left: 1em; margin-bottom: 0.3em; }
  }
  .home-links { margin-top: 0; }
  .home-toggle {
    display: inline-block;
    font-size: 0.72em;
    font-weight: 600;
    letter-spacing: 0.09em;
    text-transform: uppercase;
    color: #6f777d !important;
    text-decoration: none !important;
    border-bottom: 1px solid transparent;
    padding-bottom: 1px;
    transition: color 0.15s, border-color 0.15s;
  }
  .home-toggle:hover { color: #2f3538 !important; border-bottom-color: #2f3538; }
</style>

<div class="home-intro">
<p>Welcome! I am a PhD candidate in Economics at the University of Oxford.</p>

<p>My main research interest is in econometrics, with a focus on networks. Network data are often incomplete, and I develop tools for partially observed networks. I also work on applied projects on international trade.</p>

<p>I am on the 2026–27 academic job market.</p>
</div>

<h2 class="home-section">Education</h2>

<div class="edu">
  <div class="edu-school">University of Oxford</div>
  <div class="edu-degree">PhD in Economics</div>
  <div class="edu-year">2023–2027</div>
  <div class="edu-degree">MPhil in Economics</div>
  <div class="edu-year">2021–2023</div>
  <div class="edu-school">University of California, Berkeley</div>
  <div class="edu-degree">BA in Applied Mathematics, Economics, and Statistics</div>
  <div class="edu-year">2016–2020</div>
</div>

<h2 class="home-section">CV</h2>

<div class="home-links">
  <a href="/files/CV_Xu.pdf" class="home-toggle">Curriculum Vitae (PDF)</a>
</div>