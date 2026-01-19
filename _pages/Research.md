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

/* Divider between sub-projects inside one card */
.project-divider {
  border: none;
  border-top: 1px solid #e0e0e0;
  margin: 18px 0;
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
  <a href="#project2">Observational Health Policy Studies</a>
  <a href="#project3">Longitudinal Health Economics & Utilization</a>
  <a href="#project4">Mental Health</a>
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
 <li>
  Published in <em>JAMA Network Open</em> (2023).
  <a href="https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2801347" target="_blank">
   Full text
  </a>
</li>
  </ul>

</section>

<span class="anchor" id="project2"></span>
<section class="project-card">


  <p class="project-title">
    Impact of Regional Surgeon Competition on Breast Reconstruction Use, Cost, and Outcomes After Mastectomy
  </p>

  <p><strong>Research question addressed:</strong><br>
  To evaluate how regional surgeon competition influences access to breast reconstruction, healthcare costs, and patient outcomes following mastectomy.
  </p>

  <p class="project-subtitle"><strong>Study design and data:</strong></p>
  <ul>
    <li>Cross-sectional observational study using MarketScan insurance claims data (2009–2020)</li>
    <li>Market-level surgeon competition quantified using the Herfindahl–Hirschman Index (HHI)</li>
  </ul>

  <p class="project-subtitle"><strong>My role:</strong></p>
  <ul>
    <li>Conducted multivariable regression analyses to assess associations between market competition, utilization, and healthcare costs</li>
    <li>Evaluated disparities in access and outcomes across regions with varying levels of surgeon competition</li>
    <li>Contributed to interpretation of policy-relevant findings related to market structure and patient care</li>
  </ul>

  <p class="project-subtitle"><strong>Impact and outcome:</strong></p>
  <ul>
    <li>Provided evidence on how regional market competition shapes access to reconstructive surgery after mastectomy</li>
    <li>Highlighted economic and utilization consequences of surgeon market concentration</li>
  <li>
  Published in <em>Plastic and Reconstructive Surgery</em> (2025).
  <a href="https://journals.lww.com/plasreconsurg/fulltext/2025/03000/impact_of_regional_surgeon_competition_on_use,.8.aspx"
     target="_blank">
    Full text
  </a>
</li>
  </ul>
  
<hr class="project-divider">

 <p class="project-title">
    Factors in Hand Surgery Access for Rheumatoid Arthritis Before vs After the Affordable Care Act
  </p>

  <p><strong>Research question addressed:</strong><br>
  To assess changes in access to hand surgery for patients with rheumatoid arthritis before versus after the implementation of the Affordable Care Act, with a focus on disparities in utilization, timing, and cost.
  </p>

  <p class="project-subtitle"><strong>Study design and data:</strong></p>
  <ul>
    <li>Cross-sectional observational study using national surgical data (2009–2020)</li>
    <li>Primary outcomes included time to surgery, surgical incidence, and healthcare costs</li>
  </ul>

  <p class="project-subtitle"><strong>My role:</strong></p>
  <ul>
    <li>Conducted statistical analyses comparing pre- and post-ACA cohorts</li>
    <li>Applied multivariable regression and piecewise linear regression to evaluate changes in access over time</li>
    <li>Assessed disparities by insurance status and urbanicity</li>
    <li>Contributed to interpretation of access and cost outcomes</li>
  </ul>

  <p class="project-subtitle"><strong>Impact and outcome:</strong></p>
  <ul>
    <li>Quantified policy-associated changes in surgical access for patients with rheumatoid arthritis</li>
    <li>Identified persistent disparities in access related to insurance coverage and geographic factors</li>
   <li>
  Published in <em>JAMA Surgery</em> (2024).
  <a href="https://jamanetwork.com/journals/jamasurgery/fullarticle/2814271"
     target="_blank">
    Full text
  </a>
</li>
  </ul>
</section>

<span class="anchor" id="project3"></span>
<section class="project-card">


  <p class="project-title">
    Healthcare Utilization and Economic Outcomes of Thumb CMC Arthroplasty: Nationwide Claims-Based Analyses
  </p>

  <p><strong>Overview:</strong><br>
  A series of observational studies using nationwide insurance claims data to evaluate treatment strategies, revision risk, and long-term healthcare utilization and costs associated with thumb carpometacarpal (CMC) arthroplasty.
  </p>

  <p class="project-subtitle"><strong>Study components:</strong></p>
  <ul>
    <li>
      <strong>Surgical vs Nonoperative Management of Thumb CMC Arthritis</strong><br>
      Compared long-term healthcare costs and utilization between operative and nonoperative treatments using generalized linear mixed-effects models with propensity score matching.<br>
      Published in <em>The Journal of Hand Surgery (Asian-Pacific Volume)</em> (2024).
    </li>

    <li>
      <strong>Revision Thumb CMC Arthroplasty: Risk Factors and Economic Implications</strong><br>
      Identified patient- and treatment-related risk factors for revision surgery using multivariable logistic regression, and quantified the impact of revision procedures on long-term healthcare cost and utilization using GLMMs with propensity score weighting.<br>
      <li>
  Published in <em>Plastic and Reconstructive Surgery</em> (2025).
  <a href="https://journals.lww.com/plasreconsurg/abstract/9900/revision_thumb_cmc_arthroplasty__risk_factors_and.2882.aspx"
     target="_blank">
   Full text
  </a>
    </li>


  <p class="project-subtitle"><strong>My role:</strong></p>
  <ul>
    <li>Designed and conducted claims-based observational analyses across multiple related studies</li>
    <li>Applied causal adjustment techniques, including propensity score matching and weighting</li>
    <li>Implemented generalized linear mixed-effects models for longitudinal cost and utilization outcomes</li>
    <li>Collaborated with clinicians on interpretation of economic and surgical outcomes</li>
  </ul>

  <p class="project-subtitle"><strong>Impact:</strong></p>
  <ul>
    <li>Provided comprehensive evidence on long-term economic consequences of thumb CMC treatment strategies</li>
    <li>Informed clinical decision-making and health policy considerations regarding surgical management and revision risk</li>
    <li>Demonstrated the value of real-world evidence for evaluating surgical outcomes at the population level</li>
  </ul>

</section>


<span class="anchor" id="project4"></span>
<section class="project-card">

  <p class="project-title">
    An Effective Short Form of the UCLA Loneliness Scale: Item Response Theory and Network Psychometrics
  </p>

  <p><strong>Research question addressed:</strong><br>
  To develop and validate a shortened version of the UCLA Loneliness Scale that preserves psychometric reliability and construct validity while reducing respondent burden.
  </p>

  <p class="project-subtitle"><strong>Study design and data:</strong></p>
  <ul>
    <li>Combined cohort sample of community-dwelling adults</li>
    <li>Questionnaire-based psychometric assessment data</li>
  </ul>

  <p class="project-subtitle"><strong>My role:</strong></p>
  <ul>
    <li>Applied item response theory using graded response models to guide item reduction</li>
    <li>Conducted exploratory and confirmatory factor analyses, including tests of measurement invariance</li>
    <li>Performed network psychometric analyses to assess information retention and construct structure</li>
  </ul>

  <p class="project-subtitle"><strong>Impact and outcome:</strong></p>
  <ul>
    <li>Developed a concise, psychometrically sound short form of a widely used loneliness scale</li>
    <li>Facilitated efficient assessment in large-scale surveys and clinical research settings</li>
    <li>
  Published in <em>General Psychiatry</em> (2025).
  <a href="https://gpsych.bmj.com/content/38/4/e102055"
     target="_blank">
    Full text
  </a>
</li>
  </ul>
</section>
</section>
