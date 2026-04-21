---
layout: page
title: Research
description: Emily Maxwell Outland's research in explainable AI, human-machine teaming, and bioastronautics.
---

I am driven by a simple conviction: that humans and autonomous systems are better together than either is alone. My work sits at the intersection of human factors and autonomy — asking how we design machines that genuinely serve the humans working alongside them, rather than the other way around. The thread running through my projects is the question of *transparency*: what does it mean for a system to be truly understandable to the person depending on it?

Right now, I'm particularly interested in two directions. The first is explainable planning — how can autonomous and multi-agent systems convey their reasoning to non-expert users in ways that actually build appropriate trust and comprehension, not just the appearance of it? The second is physiological state modeling in operational contexts: can we use passive wearable sensing to track where someone's emotional state is *heading*, so that systems can adapt proactively rather than reactively? Spaceflight is my motivating application — isolated, resource-constrained, high-stakes environments where human-machine teaming genuinely matters.

---

## Research Areas

- Explainable AI for autonomous and multi-agent systems
- Human-machine teaming, trust calibration, and appropriate reliance
- Sampling-based motion planning and path legibility
- Physiological and affective state modeling
- Human factors in spaceflight and isolated, confined, extreme (ICE) environments

---

## Current Projects

<div class="project-grid">

  <div class="project-card">
    <div class="project-meta">Master's Thesis &middot; March 2026 – Present</div>
    <h3>Longitudinal Affective State Trajectory Modeling</h3>
    <span class="tag tag--blossom" style="margin-bottom:0.75rem;">Thesis</span>
    <p>
      Models human affective state as a continuous latent trajectory — valence and arousal
      over time — estimated from multimodal wearable and self-report data. Uses the
      GRU-ODE-Bayes framework applied to the LifeSnaps dataset (n&nbsp;=&nbsp;71, 4 months,
      Fitbit Sense). The latent space is grounded in the Russell circumplex via a fixed
      psychometric rotation, addressing a construct validity gap in existing HRI models.
    </p>
    <p>
      Motivating application: real-time emotional state awareness for adaptive autonomy in
      long-duration spaceflight, where isolation and circadian disruption compound over months.
    </p>
  </div>

  <div class="project-card">
    <div class="project-meta">Research Proposal / Experimental Pilot &middot; January 2026 – Present</div>
    <h3>Evaluating Comprehension for Multi-Agent Explainable Path Planning</h3>
    <span class="tag tag--sage" style="margin-bottom:0.75rem;">In Progress</span>
    <p>
      Designing an experiment to evaluate how well users understand and trust a multi-agent
      explainable planner that uses path segmentation to communicate intent. Incorporates
      validated surveys for comprehension and trust calibration with counterbalanced
      explanation conditions.
    </p>
  </div>

  <div class="project-card">
    <div class="project-meta">AFRL SMART Scholar &middot; Summer 2025</div>
    <h3>LLMs for Satellite Operator Assistance</h3>
    <span class="tag tag--mist" style="margin-bottom:0.75rem;">In Progress</span>
    <p>
      Exploring the use of large language models to assist satellite operators in task
      identification and execution at the Air Force Research Lab Space Vehicles Directorate.
    </p>
  </div>

</div>

---

## Publications

**Maxwell, E.\*, Kricheff, S.\*, Plaks, C.\*, & Simon, M.** (2024). An Explainable Machine Learning Approach for Anomaly Detection in Satellite Telemetry Data. *IEEE Aerospace Conference Proceedings 2024*. Published May 13, 2024; Presented March 7, 2024.

Applied SHAP, LIME, and Layer-wise Relevance Propagation to a novel IF-CBLOF (Isolation Forest Clustering-Based Local Outlier Factor) model and LSTM Neural Network to detect, score, and explain anomalies in satellite telemetry data.

<small><em>* indicates equal contribution as first authors</em></small>

---

## Lab Affiliations

**ARIA Systems Lab** — University of Colorado Boulder  
Led by Prof. Morteza Lahijanian, the ARIA Systems Group develops theoretical foundations and computational frameworks for autonomous systems that operate safely alongside humans. The lab integrates formal methods, motion planning under uncertainty, and multi-agent coordination to build correct-by-construction autonomous systems — the backbone of my work on explainable planning and legible robot behavior.

**Arquilla Group** — University of Colorado Boulder  
Co-advised by Prof. Katya Arquilla. The Arquilla Group takes a human-centered approach to human-automation interactions and behavioral health in operational environments, using psychophysiological monitoring and wearable sensing — directly informing the spaceflight motivation behind my thesis work.

**Air Force Research Lab — Space Vehicles Directorate**  
SMART Scholar (2023–present), with three summers of research in explainable ML, control system optimization, and LLM-assisted satellite operations.

---

[Read Research Notes &rarr;](/writing/research/)
