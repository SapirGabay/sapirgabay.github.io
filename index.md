---
layout: default
title: "Sapir Gabay"
---

<!-- Top Navigation Bar -->
<style>
.top-nav {
  position: sticky;
  top: 0;
  background: white;
  padding: 10px 0;
  border-bottom: 1px solid #e5e5e5;
  z-index: 1000;
}

.top-nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 25px;
  margin: 0;
  padding: 0;
}

.top-nav a {
  text-decoration: none;
  color: #333;
  font-size: 0.95rem;
}

.top-nav a:hover {
  text-decoration: underline;
}
</style>

<nav class="top-nav">
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#resume">Resume</a></li>
  </ul>
</nav>

<style>
/* Container width */
.main-content {
  max-width: 850px;
  margin: 0 auto;
  padding-top: 20px;
}

/* Hero */
.hero {
  margin-bottom: 35px;
}

.hero h1 {
  font-size: 2.3rem;
  margin-bottom: 0.2rem;
}

.hero h2 {
  font-size: 1.1rem;
  font-weight: 400;
  color: #555;
  margin-top: 0;
}

.hero-text {
  margin-top: 10px;
  color: #444;
}

/* Buttons */
.button-row {
  margin-top: 15px;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.btn {
  padding: 6px 14px;
  border-radius: 4px;
  font-size: 0.9rem;
  text-decoration: none;
  border: 1px solid #333;
  color: #333;
}

.btn:hover {
  background: #f0f0f0;
}

.btn-primary {
  background: #333;
  color: white;
}

/* Sections */
section {
  margin-bottom: 40px;
}

section h3 {
  margin-bottom: 10px;
}

/* Tables */
table {
  margin-top: 10px;
}

.project-item {
  margin-bottom: 20px;
}
  .project-hero {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  align-items: flex-start;
  margin-bottom: 30px;
}

.project-hero-text {
  flex: 1 1 260px;
}

.project-hero-image {
  flex: 1 1 260px;
}

.project-hero-image img {
  width: 100%;
  max-width: 520px;
  border-radius: 6px;
  border: 1px solid #e0e0e0;
}

</style>

## 📌 About Me <a id="about"></a> 

**Sapir Gabay** - Industrial Engineering & Management graduate, Ben-Gurion University (Intelligent Systems, GPA 87)

- Building ETL pipelines and Power BI dashboards with large-scale datasets (millions of rows) for tech and SaaS companies, analyzing ARR, Churn, Cohort retention, and other key metrics
- Evaluated deep-tech startups and built an early-stage investor community at BGU's entrepreneurship center
- Hands-on builder - SQL, Python, and independent AI/automation projects (n8n, Claude Code)

*A few projects I've worked on:*

---
## 💻 Technical Skillset <a id="skills"></a>

| **Programming & Data** | Python (Pandas, Scikit-learn), SQL, Java, Streamlit, Power BI, Tableau, Alteryx, Excel (Pivot Tables, Power Query, VBA) |
| **Machine Learning** | Sentiment Classification, Decision Trees, MLP, SVM |
| **AI, Automation & Deployment** | REST APIs, Claude Code, n8n, Netlify, GitHub |

---
## 🚀 Projects <a id="projects"></a>

<div class="project-hero">
  <div class="project-hero-text">
    <h3>A/B Testing for LLM Impact (Final Thesis)</h3>
    <p>
      Built a Python-based A/B testing environment using the OpenAI API to evaluate
      LLM impact on user decision-making within BI dashboards.
    </p>
  </div>

  <div class="project-hero-image">
    <img src="thesis_screenshot.png" alt="A/B testing dashboard with AI assistant">
  </div>
</div>

<div class="project-hero">
  <div class="project-hero-text">
    <h3>Interactive Portfolio Optimization</h3>
    <p>
      An interactive web application demonstrating Modern Portfolio Theory (Markowitz Model).
      Built in Python and deployed with Streamlit. Analyzes risk, return, and optimal asset
      allocation for investors.
    </p>
    <p>
      <a href="https://markowitz-portfolio-optimizer.streamlit.app/" target="_blank">
        Open live app
      </a>
    </p>
  </div>

  <div class="project-hero-image">
    <a href="https://markowitz-portfolio-optimizer.streamlit.app/" target="_blank">
      <img src="markowitz_app.png" alt="Interactive Portfolio Optimization screenshot">
    </a>
  </div>
</div>

<div class="project-hero">
  <div class="project-hero-text">
    <h3>Machine Learning: Sentiment Classification</h3>
    <p>
      Demonstrates a full ML workflow on Twitter text data, including preprocessing,
      feature engineering, model comparison and evaluation.
    </p>
    <p>
      <a href="projects/ml_sentiment_analysis.html">
        Project Link
      </a>
    </p>
  </div>

  <div class="project-hero-image">
    <a href="projects/ml_sentiment_analysis.html">
      <img src="ROC_curve.png" alt="ROC curve for sentiment classification model">
    </a>
  </div>
</div>


### Core ML Implementation: Decision Tree from Scratch  
[Project Link](projects/decision_tree_from_scratch.html)  
Implemented core ML algorithms (Decision Tree, K-Means, Chi-Squared Pruning) from scratch.

---
## 📄 Resume <a id="resume"></a>
[Download Full Resume (PDF)](https://drive.google.com/file/d/10iCzBdPtQXleXRPWRyD9qYYb6Oky6kcy/view?usp=sharing)
