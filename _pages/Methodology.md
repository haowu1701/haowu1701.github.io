---
layout: archive
title: "Methodology Research"
permalink: /Methodology/
author_profile: true
---
<style>
/* Top local navigation bar (sticky) */
.research-top-nav {
  position: sticky;
  top: 70px; /* adjust if it overlaps the main site header */
  z-index: 10;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 10px 0 25px 0;
  padding: 10px 0;
  border-bottom: 1px solid #e0e0e0;
  background: #ffffff; /* so it doesn't show content underneath when sticky */
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

/* Project cards: text left, figure right */
.project-card {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
  margin: 25px 0 35px 0;
  padding: 20px 22px;
  border-radius: 14px;
  background: #fafafa;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
  border: 1px solid #e3e3e3;
}

.project-text {
  flex: 1.2;
  min-width: 260px;
}

.project-text h2 {
  font-size: 1.45rem;
  margin-top: 0;
  margin-bottom: 10px;
}

.project-text p {
  margin: 0 0 8px 0;
}

.project-text ul {
  margin-top: 6px;
}

/* Right-side figure */
.project-image {
  flex: 0.9;
  min-width: 220px;
  text-align: center;
}

.project-image img {
  width: 100%;
  max-width: 340px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.10);
}

.project-image .caption {
  margin-top: 8px;
  font-size: 0.9rem;
  color: #666;
  font-style: italic;
}

/* Learn more button */
.learn-more-btn {
  display: inline-block;
  margin-top: 10px;
  padding: 6px 14px;
  border-radius: 999px;
  background: #0056b3;
  color: #ffffff !important;
  text-decoration: none;
  font-size: 0.9rem;
  font-weight: 500;
  transition: background 0.2s, transform 0.1s;
}

.learn-more-btn:hover {
  background: #003f82;
  transform: translateY(-1px);
}

/* Mobile: stack text and image vertically */
@media (max-width: 900px) {
  .project-card {
    flex-direction: column;
    align-items: flex-start;
  }
  .research-top-nav {
    top: 60px;
  }
  .project-image {
    text-align: left;
  }
  .project-image img {
    max-width: 100%;
  }
}
</style>

<!-- Local navigation bar at the top (sticky) -->
<nav class="research-top-nav">
  <a href="#project1">Semiparametric Theory</a>
  <a href="#project2">Causal Inference and Missing Data</a>
 
</nav>

---
My research focuses on semiparametric and causal inference methods, with emphasis on the following areas:

### 📌 Semiparametric Theory
- Efficient influence functions (EIF)   
- Asymptotic variance estimation under model misspecification
- Double/debiased machine learning (DML)

### 📌 Causal Inference
- Doubly robust estimation  
- Quantile treatment effects (QTE)
- Probablity treatment effects (PTE)


### 📌 Others
- Cumulative probability models (CPM)
- Clustered randomized clinical trials (CRCT)
- High-dimensional confounding adjustment
- Longitudinal missingness



