---
layout: page
title: CV
description: Curriculum Vitae — Emily Maxwell Outland, Graduate Researcher, CU Boulder.
---

<button class="btn btn--ghost btn--print" onclick="window.print()">Print / Save as PDF</button>
<p class="print-note">In the print dialog, uncheck &ldquo;Headers and footers&rdquo; for a clean PDF.</p>

---

<div class="cv-section">
<h2>Education</h2>

<div class="cv-entry">
  <div class="cv-entry-header">
    <h3>MS in Aerospace Engineering Science</h3>
    <span class="cv-entry-date">Expected May 2027</span>
  </div>
  <div class="cv-entry-org">University of Colorado Boulder &mdash; Boulder, CO</div>
  <p style="font-size:0.92rem; color:var(--color-warm-gray);">Focus Area: Bioastronautics</p>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <h3>BS in Computer Engineering</h3>
    <span class="cv-entry-date">May 2025</span>
  </div>
  <div class="cv-entry-org">Rose-Hulman Institute of Technology &mdash; Terre Haute, IN</div>
  <p style="font-size:0.92rem; color:var(--color-warm-gray);">Minors: Mathematics, Music</p>
</div>
</div>

---

<div class="cv-section">
<h2>Experience</h2>

<div class="cv-entry">
  <div class="cv-entry-header">
    <h3>Graduate Researcher</h3>
    <span class="cv-entry-date">August 2025 – Present</span>
  </div>
  <div class="cv-entry-org">ARIA Systems Lab &mdash; University of Colorado Boulder</div>
  <ul>
    <li>Research into explainable multi-agent motion planning and human mental state modeling</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <h3>SMART Scholar</h3>
    <span class="cv-entry-date">2023 – Present</span>
  </div>
  <div class="cv-entry-org">Air Force Research Lab &mdash; Space Vehicles Directorate</div>
  <ul>
    <li><strong>Summer 2025:</strong> Exploring LLMs to assist satellite operators in task identification and execution (in progress)</li>
    <li><strong>Summer 2024:</strong> Explored the viability of applying genetic algorithms to control system optimization (concluded, not published)</li>
    <li><strong>Summer 2023:</strong> Explored explainable machine learning methods to detect anomalies in satellite telemetry data (published)</li>
  </ul>
</div>
</div>

---

<div class="cv-section">
<h2>Publications</h2>

<div class="cv-entry">
  <p>
    <strong>Maxwell, E.*</strong>, Kricheff, S.*, Plaks, C.*, &amp; Simon, M. (2024).
    An Explainable Machine Learning Approach for Anomaly Detection in Satellite Telemetry Data.
    <em>IEEE Aerospace Conference Proceedings 2024.</em>
    Published May 13, 2024; Presented March 7, 2024.
  </p>
  <ul>
    <li>Applied SHAP, LIME, and Layer-wise Relevance Propagation to a novel IF-CBLOF model and LSTM Neural Network to detect, score, and explain anomalies in satellite telemetry data</li>
    <li>Created and evaluated Hybrid IF-CBLOF Model for Anomaly Scoring</li>
  </ul>
  <p style="font-size:0.82rem; color:var(--color-mist); margin-top:0.5rem;"><em>* equal contribution as first authors</em></p>
</div>
</div>

---

<div class="cv-section">
<h2>Projects</h2>

<div class="cv-entry">
  <div class="cv-entry-header">
    <h3>The Mad HATter</h3>
    <span class="cv-entry-date">August – December 2025</span>
  </div>
  <div class="cv-entry-org">Exploring the Effects of Autonomous Agent Personality on Human-Agent Team Dynamics</div>
  <ul>
    <li>Designed within-subjects study manipulating AI apology tone and error rate to measure effects on trust, workload, and agent perception</li>
    <li>Found apology quality significantly predicted trust (F(2,39)&nbsp;=&nbsp;8.38, p&nbsp;&lt;&nbsp;.001); rude apologies produced lower trust than no apology</li>
    <li>Identified apology fatigue: higher apology frequency decreased trust independent of tone (&asymp;&nbsp;&minus;0.49&nbsp;units/SD)</li>
    <li>Good apologies partially mitigated trust loss under high AI error conditions — implications for agent personality design in human-machine teaming</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <h3>Explainable Sampling-Based Motion Planning</h3>
    <span class="cv-entry-date">August – December 2025</span>
  </div>
  <div class="cv-entry-org">Comparing Saliency and Text-Based Explanations for RRT Path Understanding</div>
  <ul>
    <li>Implemented modified RRT with inverse-density sampling and grid-based statistical tracking across 1,000 Monte Carlo trials</li>
    <li>Developed dual-modality explanation system: saliency heatmaps and interactive contrastive text explanations via k-medoids clustering</li>
    <li>Designed counterbalanced within-subjects experimental protocol (N&nbsp;=&nbsp;24, Latin square) to evaluate explanation effectiveness on human path prediction accuracy</li>
    <li>Validated on three workspace types; identified Hausdorff distance limitations in topologically complex environments</li>
  </ul>
</div>
</div>

---

<div class="cv-section">
<h2>In Progress</h2>

<div class="cv-entry">
  <div class="cv-entry-header">
    <h3>Longitudinal Affective State Trajectory Modeling</h3>
    <span class="cv-entry-date">March 2026 – Present</span>
  </div>
  <div class="cv-entry-org">Master's Thesis</div>
  <ul>
    <li>Models human affective state as a continuous latent trajectory x(t)&nbsp;=&nbsp;[valence(t),&nbsp;arousal(t)] in the Russell circumplex, estimated from multimodal wearable and self-report data (LifeSnaps dataset, n&nbsp;=&nbsp;71, Fitbit Sense, 4 months)</li>
    <li>Uses GRU-ODE-Bayes framework with mixed continuous/categorical observation model; latent space grounded in validated psychometric rotation from PANAS to circumplex space</li>
    <li>Addresses construct validity gap in existing human state models in HRI and affective computing</li>
    <li>Motivating application: real-time emotional state awareness for adaptive autonomy in long-duration spaceflight and ICE environments</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <h3>Evaluating Comprehension and Explainability for Multi-Agent Explainable Path Planning</h3>
    <span class="cv-entry-date">January 2026 – Present</span>
  </div>
  <div class="cv-entry-org">Research Proposal / Experimental Pilot</div>
  <ul>
    <li>Designing an experiment to evaluate comprehension and intuitiveness of a multi-agent explainable planner using path segmentation</li>
    <li>Incorporating validated surveys for comprehension and trust with counterbalanced explanation conditions</li>
    <li>Running a small pilot to build a proposal for continuation of this research area</li>
  </ul>
</div>
</div>

---

<div class="cv-section">
<h2>Research Methods &amp; Expertise</h2>

<table class="cv-table">
  <tr>
    <td>Experimental Design</td>
    <td>Within-/between-subjects, Latin square counterbalancing, IRB protocols, power analysis</td>
  </tr>
  <tr>
    <td>Statistical Analysis</td>
    <td>Repeated-measures ANOVA, Tukey HSD, ANCOVA, Shapiro-Wilk, Levene's test</td>
  </tr>
  <tr>
    <td>Human Factors &amp; HRI</td>
    <td>NASA-TLX, trust measurement (Likert composites) and calibration, human-agent teaming</td>
  </tr>
  <tr>
    <td>Programming</td>
    <td>Python, Julia, R, C/C++, MATLAB, Java, AI-assisted programming</td>
  </tr>
  <tr>
    <td>ML &amp; Motion Planning</td>
    <td>Reinforcement learning (MDP/POMDP), sampling planners, explainable planning, multi-agent planning</td>
  </tr>
  <tr>
    <td>Autonomous Systems</td>
    <td>Explainable AI (XAI), LLMs for operator assistance, satellite telemetry analysis, robotics</td>
  </tr>
  <tr>
    <td>Technical Writing</td>
    <td>Conference paper and presentation, peer review experience, LaTeX</td>
  </tr>
  <tr>
    <td>Space Medicine</td>
    <td>Autonomic nervous system physiology, HRV as a biomarker, psychosocial isolation in ICE environments</td>
  </tr>
  <tr>
    <td>Languages</td>
    <td>Native English, Elementary Japanese</td>
  </tr>
</table>
</div>

---

<div class="cv-section">
<h2>Research Visions</h2>

<ul>
  <li><em>How can we design AI systems for spaceflight rather than demanding adaptation from the human?</em></li>
  <li><em>Can HRV serve as a real-time, personalized feedback signal for astronaut cognitive and autonomic state during EVA, and can that signal inform adaptive autonomy?</em></li>
  <li><em>What does it mean for a motion planner to be truly explainable to a non-expert, and does better explanation actually produce better human-robot collaboration?</em></li>
</ul>
</div>
