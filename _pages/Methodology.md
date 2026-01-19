---
layout: archive
title: "Methodology Research"
permalink: /Methodology/
author_profile: true
---

<style>
/* Anchor spacer to avoid sticky nav overlap */
.anchor {
  display: block;
  height: 0;
  position: relative;
  top: -120px; /* = 你的 header + nav 的总遮挡高度，110~140 之间调 */
  visibility: hidden;
}


  /* Tight spacing between subsection title and bullets in project cards */
.project-card .project-subtitle {
  margin-top: 10px;
  margin-bottom: 5px;  /* 关键：压缩与 ul 的距离 */
}

/* Project title styling */
.project-title {
  font-size: 1.15rem;      /* 比正文大一点 */
  font-weight: 600;        /* 接近论文标题粗细 */
  margin-top: 6px;
  margin-bottom: 10px;
  line-height: 1.35;
}

/* Indented overview section */
.overview-section {
  margin-left: 1.5em;   /* 控制“右缩进几格”，可调 */
}

/* Overview titles: not bold */
.overview-section h3 {
  font-weight: 400;     /* normal，不加粗 */
  margin-top: 6px;
  margin-bottom: 4px;
}

/* Keep overview bullets compact */
.overview-list {
  margin-top: 0;
  margin-bottom: 8px;
}

.overview-list li {
  line-height: 1.25;
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
<div class="overview-section">
<h3>📌 Semiparametric Theory</h3>
<ul class="overview-list">
  <li>Efficient influence functions · Asymptotic variance estimation under model misspecification · Double/debiased machine learning </li>
</ul>

<h3>📌 Causal Inference</h3>
<ul class="overview-list">
  <li>Doubly robust estimation · Quantile treatment effects (QTE) · Probability treatment effects (PTE)</li>
</ul>

<h3>📌 Other Topics</h3>
<ul class="overview-list">
  <li>Semiparametric cumulative probability models · Longitudinal missingness</li>
</ul>
</div>

 <strong> Below are 3 completed methodology projects from my PhD to date.</strong><br>
<!-- Sticky nav placed AFTER the sentence -->

<nav class="research-top-nav">
  <a href="#project1">Doubly Robust Estimators of QTE/PTE</a>
  <a href="#project2">Doubly Robust Varaince Estimator</a>
  <a href="#project3">AWGEE with Longitudinal Missingness</a>
</nav>

<span class="anchor" id="project1"></span>
<section class="project-card">
<p class="project-title">
  Doubly Robust Estimators of Quantile Treatment Effects with Semiparametric Cumulative Probability Models
</p>

  <p class="project-subtitle"><strong>Problem addressed:</strong><br>
  In real-world evidence studies, outcomes are often highly skewed and subject to detection limits, making mean-based causal analyses unstable.
  </p>

  <p class="project-subtitle"><strong>My contribution:</strong></p>
  <ul>
    <li>Developed a doubly robust framework for quantile and probability treatment effects using semiparametric cumulative probability models</li>
    <li>Implemented efficient influence function–based estimators with valid variance estimation</li>
  </ul>

  <p class="project-subtitle"><strong>Why this matters:</strong></p>
  <ul>
    <li>Captures treatment effects across the entire outcome distribution, not just the mean</li>
    <li>Provides robust inference under partial model misspecification</li>
    <li>Directly applicable to observational studies with skewed outcomes or detection limits</li>
  </ul>

  <p class="project-subtitle"><strong>Technical skills demonstrated:</strong></p>
  <ul>
    <li>Doubly robust estimation · QTE / PTE · Semiparametric modeling</li>
    <li>Monte Carlo simulation and bootstrap inference</li>
    <li>Analysis of real biomedical data (HIV studies)</li>
  </ul>
</section>

<span class="anchor" id="project2"></span>
<section class="project-card">
 <p class="project-title">
    Why Double Robustness Does Not Extend to Variance Estimation Under Parametric Nuisance Models?
  </p>

  <p class="project-subtitle"><strong>Problem addressed:</strong><br>
  In practice, influence function–based variance estimators are routinely used alongside doubly robust point estimators. While double robustness guarantees consistency of point estimation under partial model misspecification, no such guarantee exists for variance estimation.
  </p>

  <p class="project-subtitle"><strong>My contribution:</strong></p>
  <ul>
    <li>Developed a formal theoretical framework explaining why double robustness does not extend to variance estimation under parametric nuisance models</li>
    <li>Proposed alternative variance estimation strategies, including joint inference, sample-splitting-cross-fitting, with theoretical guarantees under model misspecification</li>
  </ul>

  <p class="project-subtitle"><strong>Why this matters:</strong></p>
  <ul>
    <li>Reveals hidden risks in uncertainty quantification for causal analyses in observational studies</li>
    <li>Provides practical guidance for valid inference in real-world settings where working models may be misspecified</li>
  </ul>

  <p class="project-subtitle"><strong>Technical skills demonstrated:</strong></p>
  <ul>
    <li>Semiparametric theory · Influence functions · Doubly robust estimation</li>
    <li>Asymptotic analysis </li>
    <li>Monte Carlo simulation · Real-data analysis</li>
  </ul>
</section>

<span class="anchor" id="project3"></span>
<section class="project-card">
  <p class="project-title">
    A Simple Augmentation of Weighted Generalized Estimating Equations for Doubly Robust Estimation in Longitudinal Data with Missingness
  </p>

  <p><strong>Clinical and statistical problem addressed:</strong><br>
  In longitudinal studies, monotone missing outcomes are common and can severely bias inference. Standard approaches, such as outcome imputation or inverse probability weighting (IPW), are often highly sensitive to model misspecification.
  </p>

  <p class="project-subtitle"><strong>My contribution:</strong></p>
  <ul>
    <li>Developed a doubly robust estimator, the Augmented Weighted Generalized Estimating Equation (AWGEE), for longitudinal responses with monotone dropout</li>
    <li>Unified imputation-based methods and WGEE within a single estimating equation framework</li>
    <li>Improved efficiency through augmentation with re-imputed outcomes</li>
    <li>Applied the proposed method to real longitudinal psychiatric data</li>
  </ul>

  <p class="project-subtitle"><strong>Why this matters:</strong></p>
  <ul>
    <li>Reduces sensitivity to model misspecification. </li>
    <li>Enables robust inference for longitudinal treatment effects in the presence of dropout.</li>
    <li>Reveals a common misconception in the application of doubly robust estimators to missing data problems.</li>
  </ul>

  <p class="project-subtitle"><strong>Technical skills demonstrated:</strong></p>
  <ul>
    <li>Doubly robust estimation · Longitudinal data analysis · Missing data due to dropout· Weighted Generalized estimating equations (WGEE)</li>
  </ul>
</section>

