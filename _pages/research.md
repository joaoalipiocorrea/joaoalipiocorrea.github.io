---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
filters: []
---

My current research focus on developing tools for causal inference under violations of common assumptions. In the projects listed below I adapt and evaluate design and model-based strategies to recover credible effects when treatments diffuse across networked units, or when they evolve over time.

All my working papers are available upon request. Feel free to email me if you are interested in collaborating or just curious.


# Methods

### **Synthetic Control Method under Interference: Detecting and Correcting Bias**  
*Working Paper*

<p style="font-size: 0.9em; color: #666;">
Working with synthetic control, I study how exposure to spillovers distorts identification and develop tools to detect these failures and correct for them. The approach formalizes a contamination channel driven by proximity-based spillovers and uses this structure to create a diagnostic that tests for interference. When interference is present, the corrections operate directly on the contamination pathway: either by rescaling exposure-linked covariates or by reallocating donor mass through constrained and unconstrained ridge procedures. Extensive simulations and a broad set of replications validate the ability of these adjustments to recover credible estimates even when the classic no-interference assumption breaks down.
</p>

<div style="margin-bottom: 1em;">
  <a href="/files/scm_interference_paper.pdf" class="btn btn--small btn--primary">Paper</a>
  <a href="/files/scm_interference_slides.pdf" class="btn btn--small btn--inverse">Slides</a>
</div>

---

### **Sensitivity Analysis Framework for Consistency Violations under Interference**  
*Working Paper*

<p style="font-size: 0.9em; color: #666;">
This paper explores a sensitivity analysis framework designed to give researchers a more general way to assess robustness when interference, rather than unmeasured confounding, is the source of identification failure. I extend the Bonvini and Kennedy confounded-fraction framework to settings where exposure structures are only partially known. The key insight is that, under independence of interference membership and a shared-severity envelope for spillovers, interference can be embedded in the same structure that yields sharp bounds in the confounding case. This produces a network-agnostic sensitivity model where interference bias appears as a weighted disturbance constrained by budgets on unit influence, total spillover mass, or monotonicity. The resulting bounds deliver closed-form worst-case bias and flip thresholds, and the framework naturally incorporates domain knowledge through exposure maps when available.
</p>

<div style="margin-bottom: 1em;">
  <a href="/files/sensitivity_interference_paper.pdf" class="btn btn--small btn--primary">Paper</a>
</div>

---

### **Beyond Placebos: Constructing Synthetic Interventions for Causal Inference**  
*Work-in-Progress*

<p style="font-size: 0.9em; color: #666;">
This project explores ways to construct synthetic interventions rather than relying on classic placebo-based inference. The idea is to formalize intervention design as an optimization problem: selecting donor units and weights to mimic hypothetical shocks, institutional changes, or treatment sequences that did not occur. This perspective allows researchers to probe counterfactual regimes and generate comparisons that more closely match the substantive theories motivating case studies.
</p>

---

# Applications

### **Navigating the Divide: How Unattached Voters Respond to Politically Sponsored Protests in Polarized Contexts**  
*(joint work with Laura Chelidonopoulos) — Working Paper*

<p style="font-size: 0.9em; color: #666;">
This project examines how partisan-organized demonstrations shape political behavior by combining elite interviews with a large-scale repeated-measures experiment. We begin by interviewing politicians to elicit their expectations about which voter groups are most responsive to these events and the mechanisms they believe drive heterogeneity. These elicited beliefs are then used to pre-register hypotheses, which we test using a nationally representative survey experiment that randomly assigns respondents to information about politically sponsored protests and re-interviews them after treatment. The design enables a direct comparison between elite expectations and observed behavioral responses, providing evidence on the accuracy of political actors’ beliefs and offering a framework for integrating elite knowledge into policy learning and heterogeneous treatment effect evaluation.
</p>

---

### **When Coups Fail: Causal Estimates of Economic Decline after Unsuccessful Seizures of Power**  
*Working Paper*

<p style="font-size: 0.9em; color: #666;">
This paper investigates the economic consequences of failed coup attempts. Using a global dataset of unsuccessful seizures of power, I estimate their impact on economic performance by comparing affected countries with matched counterfactual trajectories. The analysis shows that even unsuccessful coups generate substantive economic disruptions, including declines in investment, slower growth, and elevated political risk, highlighting how attempted regime change can reshape macroeconomic conditions even when it does not succeed.
</p>

---

### **Can the Resource Curse be Avoided? Assessing the Impact of a Major Oil Field Discovery on Political Participation**  
*(joint work with Laura Chelidonopoulos) — Work-in-Progress*

<p style="font-size: 0.9em; color: #666;">
This project studies the political effects of a sudden offshore oil field discovery and the associated revenue windfall for nearby coastal municipalities. We analyze how the expectation of future royalties shapes voter turnout, mobilization, and engagement with local politics. The design leverages spatial variation in exposure to the discovery and temporal variation in the announcement and institutional implementation of revenue flows, providing new evidence on how natural resource shocks influence democratic participation.
</p>

---
