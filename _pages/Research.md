---
layout: archive
title: "Collboration Research"
permalink: /Research/
author_profile: true
toc: false
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

I enjoy collaborating with domain scientists to solve real-world problems in biomedical data using modern statistical methods. Below are selected collaboration projects I have been involved in since 2023.



<!-- Local navigation bar at the top (sticky) -->
<nav class="research-top-nav">
  <a href="#project1">Longitudinal Randomized Clinical Trials</a>
  <a href="#project2">Observational Healthy Policy Studies</a>
  <a href="#project3">Longitudinal Health Economics & Utilization</a>
  <a href="#project4">project 4</a>
</nav>

---
<span class="anchor" id="project1"></span>
<section class="project-card">

  <p class="project-title">
    Comparison of Distal Radius Fracture Outcomes in Older Adults: Casting vs Surgery and Chronologic vs Physiologic Age
  </p>

  <p><strong>Clinical question addressed:</strong><br>
  To evaluate longitudinal functional outcomes following casting versus surgical management of distal radius fractures in older adults, and to assess whether physiologic age better predicts recovery trajectories than chronologic age.
  </p>

  <p class="project-subtitle"><strong>Study design and data:</strong></p>
  <ul>
    <li>Multicenter randomized clinical trial (WRIST)</li>
    <li>Repeated functional outcome measurements collected up to one year post-treatment</li>
  </ul>

  <p class="project-subtitle"><strong>My role:</strong></p>
  <ul>
    <li>Conducted longitudinal analysis using linear mixed-effects models to account for within-subject correlation</li>
    <li>Addressed confounding and performed subgroup and age-stratified analyses</li>
    <li>Collaborated closely with clinicians on interpretation and manuscript preparation</li>
  </ul>

  <p class="project-subtitle"><strong>Impact and outcome:</strong></p>
  <ul>
    <li>Provided evidence-based guidance on treatment selection for older adults with distal radius fractures</li>
    <li>Demonstrated the importance of physiologic age in predicting functional recovery</li>
    <li>Published in <em>JAMA Network Open</em> (2023)</li>
  </ul>

</section>

