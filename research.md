---
layout: page
title: Research
description: Emily Maxwell Outland's research in explainable AI, human-machine teaming, and bioastronautics.
---

<a href="/assets/EMOutland_CV-2.pdf" class="btn btn--ghost" download>Download CV (PDF)</a>

I am driven by a simple conviction: that humans and autonomous systems are better together than either is alone. My work sits at the intersection of human factors and autonomy — asking how we design machines that genuinely serve the humans working alongside them, rather than the other way around. The thread running through my projects is the question of *transparency*: what does it mean for a system to be truly understandable to the person depending on it?

Right now, I'm particularly interested in two directions. The first is explainable planning. How can autonomous and multi-agent systems convey their reasoning to non-expert users in ways that actually build appropriate trust and comprehension, not just the appearance of it? The second is related: techability for Reinforcement Learning (RL) agents. In a real operational context, where models often do not match reality, how can we explain an agent's reasoning to a human? When it is inevitably wrong in its reasoning, how can we easily correct it in the easiest modality for human comprehension: natural language?

---

## Research Areas

- Explainable AI for autonomous and multi-agent systems
- Human-machine teaming, trust calibration, and appropriate reliance
- Human physiological signals and adaptive autonomy
- Teachable AI for resilient and trustworthy autonomy

---

## Current Projects

<div class="project-grid">

  <div class="project-card">
    <div class="project-meta">Master's Thesis &middot; July 2026 – Present</div>
    <h3>Evaluating Comprehension for Multi-Agent Explainable Path Planning</h3>
    <span class="tag tag--sage" style="margin-bottom:0.75rem;">In Progress</span>
    <p>
      Exploring teachable Reinforcement Learning (RL) which explains its reasoning to a human
      in natural language and receives critique to that reasoning from a human in natural language.
      Similar to teachability in humans, the goal is to create an agent which can learn from human feedback.
    </p>
    <p>
      Motivating application: In operational environments, novel situations are the norm, not the exception.
      RL typically needs a lot of data to train, but these novel scenarios can be rare or catastrophic. What if
      a human could update the agent's understanding of cause and effect through a conversation instead? Perhaps
      one sentence could be worth a thousand simulated scenarios.
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
    <span class="tag tag--sage" style="margin-bottom:0.75rem;">In Progress</span>
    <p>
      Exploring the use of large language models to assist satellite operators in task
      identification and execution at the Air Force Research Lab Space Vehicles Directorate.
    </p>
  </div>

</div>

---

## Highlighted Past Projects

<div class="project-grid">

<div class="project-card">
    <div class="project-meta">Master's Thesis &middot; March 2026 – June 2026</div>
    <h3>Longitudinal Affective State Trajectory Modeling</h3>
    <span class="tag tag--blossom" style="margin-bottom:0.75rem;">On Hold</span>
    <p>
      Explored modeling human affective (emotional) state as a continuous latent trajectory 
      estimated from multimodal wearable data, with a latent space grounded in the 
      Russell circumplex.
    <p>
      Set aside this research direction because valence is currently impossible to measure through 
      unobtrusive wearables without self-report data. Real-time brain activity, facial muscle 
      activation, or eye-tracking would be needed to get a valence measurement with any fidelity.
    </p>
  </div>

  <div class="project-card">
    <div class="project-meta">Human Factors &middot; August – December 2025</div>
    <h3>The Mad HATter</h3>
    <span class="tag tag--mist" style="margin-bottom:0.75rem;">Completed</span>
    <p>
      Explored the effects of autonomous agent personality on human-agent team dynamics.
      Designed a within-subjects study manipulating AI apology tone and error rate to measure
      effects on trust, workload, and agent perception.
    </p>
    <p>
      Found apology quality significantly predicted trust (F(2,39)&nbsp;=&nbsp;8.38,
      p&nbsp;&lt;&nbsp;.001); rude apologies produced lower trust than no apology at all.
      Identified <em>apology fatigue</em>: higher apology frequency decreased trust independent
      of tone (&asymp;&nbsp;&minus;0.49&nbsp;units/SD). Overall, found implications for agent 
      personality design in human-machine teaming.
    </p>
  </div>

  <div class="project-card">
    <div class="project-meta">Explainable AI &middot; August – December 2025</div>
    <h3>Explainable Sampling-Based Motion Planning</h3>
    <span class="tag tag--mist" style="margin-bottom:0.75rem;">Completed</span>
    <p>
      Compared saliency and text-based explanations for RRT path understanding. Implemented
      a modified RRT with inverse-density sampling and developed a dual-modality explanation
      system: saliency heatmaps and interactive contrastive text explanations via k-medoids
      clustering.
    </p>
    <p>
      Identified Hausdorff distance, used for k-medoids clustering, has limitations in topologically 
      complex environments, and the explainability study with human participants was planned but not
      executed. This work informs the design of a potential follow-on study.
    </p>
  </div>

</div>

---

## Publications

**Maxwell, E.**\*, Kricheff, S.\*, Plaks, C.\*, & Simon, M. (2024). An Explainable Machine Learning Approach for Anomaly Detection in Satellite Telemetry Data. *IEEE Aerospace Conference Proceedings 2024*. Published May 13, 2024; Presented March 7, 2024.

Applied SHAP, LIME, and Layer-wise Relevance Propagation to a novel IF-CBLOF (Isolation Forest Clustering-Based Local Outlier Factor) model and LSTM Neural Network to detect, score, and explain anomalies in satellite telemetry data.

<small><em>* indicates equal contribution as first authors</em></small>

---

## Lab Affiliations

**ARIA Systems Lab** — University of Colorado Boulder  
Led by Prof. Morteza Lahijanian, the ARIA Systems Group develops theoretical foundations and computational frameworks for autonomous systems that operate safely alongside humans. The lab integrates formal methods, motion planning under uncertainty, and multi-agent coordination to build correct-by-construction autonomous systems.

**Arquilla Group** — University of Colorado Boulder  
Led by Prof. Katya Arquilla, the Arquilla Group takes a human-centered approach to human-automation interactions and behavioral health in operational environments, using psychophysiological monitoring and wearable sensing.

**Air Force Research Lab — Space Vehicles Directorate**  
SMART Scholar (2023–present), with four summers of research in explainable ML, control system optimization, and AI-assisted satellite operations.

---

[Read Research Notes &rarr;](/writing/research/)
