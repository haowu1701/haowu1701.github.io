---
layout: archive
title: "Methodology Research"
permalink: /Methodology/
author_profile: true
---

<style>
  /* Offset anchor scroll position for sticky nav */
.project-card {
  scroll-margin-top: 110px; /* 根据你的 nav 高度微调 */
}

/* Top local navigation bar (sticky) */
.research-top-nav {
  position: sticky;
  top: 70px;
  z-index: 10;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 10px 0 25px 0;
  padding: 10px 0;
  border-bottom: 1px solid #e0e0e0;
  background: #ffffff;
}

.research-top-nav a {
  padding: 6px 12px;
  border-radius: 999px;
  background: #f3f3f3;
  text-decoration: none;
  color: #333;
  font-size: 0.9rem;
  font-weight: 500;
  transition: background 0.2s, transform 0.1s;
}

.research-top-nav a:hover {
  background: #e0e0e0;
  transform: translateY(-1px);
}

/* Cards / frames */
.project-card {
  margin: 18px 0 22px 0;
  padding: 18px 20px;
  border-radius: 14px;
  background: #fafafa;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
  border: 1px solid #e3e3e3;
}

/* Headings inside cards */
.project-card h2, .project-card h3 {
  margin-top: 0;
  margin-bottom: 10px;
}

.project-card ul {
  margin: 0;
  padding-left: 20px;
}
</style>

<p>
My research focuses on semiparametric and causal inference methods, with emphasis on the following areas:
</p>

<!-- Sticky nav placed AFTER the sentence -->
<nav class="research-top-nav">
  <a href="#semiparametric">Semiparametric Theory</a>
  <a href="#causal">Causal Inference</a>
  <a href="#other">Other Topics</a>
</nav>

<section class="project-card" id="semiparametric">
  <h3>📌 Semiparametric Theory</h3>
  <ul>
    <li>Efficient influence functions (EIF)</li>
    <li>Asymptotic variance estimation under model misspecification</li>
    <li>Double/debiased machine learning (DML)</li>
  </ul>
</section>

<section class="project-card" id="causal">
  <h3>📌 Causal Inference</h3>
  <ul>
    <li>Doubly robust estimation</li>
    <li>Quantile treatment effects (QTE)</li>
    <li>Probability treatment effects (PTE)</li>
  </ul>
</section>

<section class="project-card" id="other">
  <h3>📌 Other Methodological Topics</h3>
  <ul>
    <li>Cumulative probability models (CPM)</li>
    <li>Clustered randomized clinical trials (CRCT)</li>
    <li>Longitudinal missingness</li>
  </ul>
</section>
