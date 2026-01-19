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
/* Compact bullet list for overview section */
.overview-list {
  margin-top: 4px;
  margin-bottom: 10px;
}

.overview-list li {
  margin-bottom: 2px;   /* 控制行间距 */
  line-height: 1.25;    /* 更紧凑但仍可读 */
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
<h3>📌 Semiparametric Theory</h3>
<ul class="overview-list">
  <li>Efficient influence functions (EIF)</li>
  <li>Asymptotic variance estimation under model misspecification</li>
  <li>Double/debiased machine learning (DML)</li>
</ul>

<h3>📌 Causal Inference</h3>
<ul class="overview-list">
  <li>Doubly robust estimation</li>
  <li>Quantile treatment effects (QTE)</li>
  <li>Probability treatment effects (PTE)</li>
</ul>

<h3>📌 Other Methodological Topics</h3>
<ul class="overview-list">
  <li>Cumulative probability models (CPM)</li>
  <li>Clustered randomized clinical trials (CRCT)</li>
  <li>Longitudinal missingness</li>
</ul>

  Below are three completed methodology projects from my PhD to date.
<!-- Sticky nav placed AFTER the sentence -->
<nav class="research-top-nav">
  <a href="#project1">Doubly Robust Estimators of QTE/PTE</a>
  <a href="#causal">Causal Inference</a>
  <a href="#other">Other Topics</a>
</nav>

<section class="project-card" id="project1">
 <p><strong>Project title:</strong><br>
  Doubly Robust Estimators of Quantile Treatment Effects with Semiparametric Cumulative Probability Models
  </p>

  <p><strong>Clinical problem addressed:</strong><br>
  In real-world evidence studies, outcomes are often highly skewed and subject to detection limits, making mean-based causal analyses unstable.
  </p>

  <p><strong>My contribution:</strong></p>
  <ul>
    <li>Developed a doubly robust framework for quantile and probability treatment effects using semiparametric cumulative probability models</li>
    <li>Implemented efficient influence function–based estimators with valid variance estimation</li>
  </ul>

  <p><strong>Why this matters for pharmaceutical and clinical research:</strong></p>
  <ul>
    <li>Captures treatment effects across the entire outcome distribution, not just the mean</li>
    <li>Provides robust inference under partial model misspecification</li>
    <li>Directly applicable to observational studies with skewed outcomes or detection limits</li>
  </ul>

  <p><strong>Technical skills demonstrated:</strong></p>
  <ul>
    <li>Doubly robust estimation · QTE / PTE · Semiparametric modeling</li>
    <li>Monte Carlo simulation and bootstrap inference</li>
    <li>Analysis of real biomedical data (HIV studies)</li>
  </ul>
</section>

