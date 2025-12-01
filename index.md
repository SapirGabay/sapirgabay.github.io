---
layout: default
title: {{ site.title }}
---

<style>
.main-content {
  max-width: 900px;
  margin: 0 auto;
}

/* Hero */
.hero {
  text-align: left;
  margin-bottom: 2.5rem;
}

.hero h1 {
  font-size: 2.4rem;
  margin-bottom: 0.3rem;
}

.hero h2 {
  font-size: 1.1rem;
  font-weight: 400;
  color: #555;
  margin-top: 0;
}

.tagline {
  display: inline-block;
  margin-top: 0.6rem;
  padding: 0.25rem 0.7rem;
  border-radius: 999px;
  border: 1px solid #e0e0e0;
  font-size: 0.85rem;
  color: #555;
}

/* Buttons */
.button-row {
  margin-top: 1.2rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
}

.btn {
  display: inline-block;
  padding: 0.45rem 0.9rem;
  border-radius: 999px;
  font-size: 0.9rem;
  text-decoration: none;
  border: 1px solid #222;
}

.btn-primary {
  background: #222;
  color: #fff;
}

.btn-outline {
  background: #fff;
  color: #222;
}

/* Section titles */
section {
  margin-bottom: 2.5rem;
}

section h3 {
  margin-bottom: 0.6rem;
}

/* Experience cards */
.experience-item {
  margin-bottom: 1rem;
}

.experience-item h4 {
  margin-bottom: 0.2rem;
}

.experience-meta {
  font-size: 0.85rem;
  color: #777;
  margin-bottom: 0.3rem;
}

/* Skills table */
.skills-table td, .skills-table th {
  padding: 0.25rem 0.4rem;
  vertical-align: top;
}

/* Projects */
.project-item {
  margin-bottom: 1.3rem;
}

.project-meta {
  font-size: 0.85rem;
  color: #777;
}
</style>

<div class="hero">
  <h1>{{ site.title }}</h1>
  <h2>B.Sc. Industrial Engineering &amp; Management · Data-Driven Solution Designer</h2>
  <span class="tagline">Final-year student · Intelligent Systems · Ben-Gurion University</span>

  <div class="button-row">
    <a class="btn btn-primary" href="https://drive.google.com/file/d/1yHBrlU0xIbWNlJ9Sc5C5NLtd09DvTyqd/view?usp=sharing" target="_blank">Download Resume (PDF)</a>
    <a class="btn btn-outline" href="mailto:{{ site.email }}">Email</a>
    <a class="btn btn-outline" href="https://github.com/{{ site.github_username }}" target="_blank">GitHub</a>
    <a class="btn btn-outline" href="{{ site.linkedin_url }}" target="_blank">LinkedIn</a>
  </div>
</div>

---

<section id="about">
  <h3>About</h3>
  <p>
    I'm Sapir, a final-year Industrial Engineering and Management student at Ben-Gurion University,
    specializing in Intelligent Systems (GPA 87).
  </p>
  <p>
    I enjoy taking a real business challenge, breaking it into a clear problem, and building practical,
    data-driven solutions – from core code and analytics to automation workflows.
    At BGU's entrepreneurship center I worked with early-stage startups and investors, performing
    deep analysis and due diligence on new ventures.
  </p>
  <p>
    I'm a rapid self-learner and love exploring new tools, especially where data, product, and automation meet.
  </p>
</section>

<section id="experience">
  <h3>Experience</h3>

  <div class="experience-item">
    <h4>Business &amp; Market Analyst · Oazis – BGU Innovation Accelerator</h4>
    <div class="experience-meta">Deep-tech commercialization · Investors · Venture screening</div>
    <ul>
      <li>Identified and evaluated deep-tech research projects for commercial potential and product–market fit.</li>
      <li>Analyzed markets, competitors, and IP landscape to support go / no-go decisions.</li>
      <li>Prepared one-pagers and materials for investors and partners; maintained relationships with early-stage VCs and alumni ventures.</li>
    </ul>
  </div>

  <div class="experience-item">
    <h4>Investment Analyst Intern · Cactus Capital (BGU VC)</h4>
    <div class="experience-meta">Early-stage VC · Market &amp; product analysis</div>
    <ul>
      <li>Built analysis reports covering market size, competition, and business models for student-led startups.</li>
      <li>Assessed business viability and risks, supporting investment committee discussions.</li>
      <li>Collaborated with founders to refine pitch, value proposition, and KPIs.</li>
    </ul>
  </div>

  <div class="experience-item">
    <h4>Branch Manager · Israeli Scouts Movement</h4>
    <div class="experience-meta">150+ members · Operations · Budget management (SAP)</div>
    <ul>
      <li>Led a branch of 150+ members including educational programs, staff management, and logistics.</li>
      <li>Managed budget and operations using SAP; coordinated with municipality and local organizations.</li>
      <li>Built partnerships to support community activities and events.</li>
    </ul>
  </div>
</section>

<section id="skills">
  <h3>Technical Skillset</h3>

  <table class="skills-table">
    <tr>
      <th>Programming &amp; Data</th>
      <td>Python (Pandas, Scikit-learn), SQL, Java, Streamlit (App Dev), Power BI, Tableau, Excel (Pivot Tables, Power Query, VBA)</td>
    </tr>
    <tr>
      <th>Machine Learning</th>
      <td>Sentiment Classification, Decision Trees, MLP, A* Search, Genetic Algorithms</td>
    </tr>
    <tr>
      <th>Automation &amp; No-Code</th>
      <td>N8N, Airtable, Notion, workflow design</td>
    </tr>
  </table>
</section>

<section id="projects">
  <h3>Projects</h3>

  <div class="project-item">
    <h4>Interactive Portfolio Optimization (Live App)</h4>
    <div class="project-meta">Modern Portfolio Theory · Python · Streamlit</div>
    <p>
      An interactive web application demonstrating Modern Portfolio Theory (Markowitz Model).
      Built end-to-end in Python and deployed with Streamlit, enabling investors to explore risk,
      return, and optimal asset allocation.
    </p>
    <p>
      <a href="https://markowitz-portfolio-optimizer.streamlit.app/" target="_blank">Live App</a>
    </p>
  </div>

  <div class="project-item">
    <h4>Decision Tree from Scratch</h4>
    <div class="project-meta">Core ML · Algorithms · Python</div>
    <p>
      Implemented core ML algorithms (Decision Tree, K-Means, Chi-Squared pruning) from scratch
      to deepen understanding of model internals and performance trade-offs.
    </p>
    <p>
      <a href="projects/decision_tree_from_scratch.html">Read more</a>
    </p>
  </div>

  <div class="project-item">
    <h4>Sentiment Classification – Text ML Pipeline</h4>
    <div class="project-meta">NLP · Model training · Evaluation</div>
    <p>
      Built an end-to-end sentiment classification pipeline on text data, including preprocessing,
      feature engineering, model training, and evaluation.
    </p>
    <p>
      <a href="projects/ml_sentiment_analysis.html">Read more</a>
    </p>
  </div>
</section>

<section id="contact">
  <h3>Contact</h3>
  <p>
    Interested in collaborating, internships, or junior roles in data / product / automation?
    Reach out at <a href="mailto:{{ site.email }}">{{ site.email }}</a> or via LinkedIn.
  </p>
</section>
