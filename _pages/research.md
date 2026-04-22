---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research develops tools for causal inference when standard identification assumptions break down. 

# Methods

<div class="paper-entry" markdown="1">

### Detection and Partial Identification of Spillover Contamination Under Interference

<span class="paper-status">Working Paper</span>

<p class="paper-teaser">Derives sharp bounds on the bias that exposed controls inject into any linear treatment effect estimator under interference. Combines a doubly robust estimate of average spillover with a closed-form sorting linear program.</p>

<details class="paper-abstract" markdown="1">
<summary>Abstract</summary>

Standard treatment effect estimators construct counterfactuals by aggregating control outcomes with estimator-specific weights. Under interference, exposed controls carry contaminated outcomes into the counterfactual, producing bias that depends on unobserved individual spillover effects. This paper detects this contamination and derives sharp bounds on its magnitude for any linear estimator. A doubly robust procedure identifies the average spillover among exposed controls under an exposure ignorability condition formalized through network or geographic distance. This identified mean then constrains a partial identification analysis: bounding the contamination reduces to a linear program solved in closed form through a sorting characterization that pairs estimator weights with unit-specific spillover capacities in monotone order.

The width of the resulting identification region is governed by weight dispersion among exposed controls. Difference-in-differences, with uniform weights, achieves point identification of the contamination; synthetic control, staggered designs, and other concentrated-weight estimators face genuine partial identification, with the width Schur-convex in the weight vector. Conditional spillover estimates tighten bounds further via a Jensen inequality on within-stratum budget flexibility. The bound mapping is piecewise linear and Lipschitz, plug-in estimators inherit doubly robust convergence rates, and inference uses Imbens-Manski confidence intervals with a spatial cluster bootstrap derived from the exposure model.

</details>

</div>

<div class="paper-entry" markdown="1">

### Synthetic Control Under Interference: Detecting and Correcting Bias

<span class="paper-status">Working Paper</span>

<p class="paper-teaser">Diagnoses and corrects synthetic control bias caused by spillovers onto high-weight donors. Introduces a distance-based randomization test and three weight-optimization adjustments using an exposure score.</p>

<details class="paper-abstract" markdown="1">
<summary>Abstract</summary>

Synthetic control constructs counterfactuals by placing large weights on a few untreated donors, making it especially sensitive to spillovers since high-weight donors are often those closest to the treated unit. This paper decomposes the resulting bias into a contamination term proportional to the weight mass on exposed donors, then develops diagnostics and corrections targeting that term. A randomization test partitions donors into distance-based rings and yields finite-sample exact p-values for proximity-patterned interference under a sharp null.

Three estimation adjustments incorporate a distance-based exposure score into the weight optimization: covariate rescaling that shifts the feasible set away from exposed donors, a simplex-constrained ridge penalty with exposure-aligned shrinkage, and an unconstrained ridge that permits negative weights and provides a tuning-monotone envelope for the contamination term. Theoretical guarantees cover support elimination, bandwise mass dominance, and bias envelope convergence. Simulations and replications of four canonical applications illustrate practical performance.

</details>

</div>

<div class="paper-entry" markdown="1">

### Causal Inference Under Structural Interventions 

<span class="paper-status">Work in Progress</span>

<p class="paper-teaser">Studies interventions that modify the network itself — adding, removing, or rewiring nodes and edges. Defines graph-valued potential outcomes and uses optimal transport to compare distributions across network topologies.</p>

<details class="paper-abstract" markdown="1">
<summary>Abstract</summary>

Most causal frameworks treat the network connecting units as fixed and intervene on units within that structure. This paper considers the complementary problem: what happens when the intervention targets the structure itself? Creating, deleting, or modifying nodes and edges changes the network through which outcomes propagate, raising distinct identification challenges that unit-level potential outcomes frameworks are not designed to handle.

The paper defines causal estimands for structural interventions on networks, formalizing how adding a node, severing a connection, or rewiring a subgraph alters the joint distribution of outcomes across the remaining units. Identification results characterize when structural effects are separable from compositional effects driven by changes in the unit population. An optimal transport framework provides a natural language for tracking how quantities flow through the modified structure and for comparing outcome distributions across network configurations that differ in topology. The approach connects interference, network formation, and distributional treatment effects under a unified potential-outcomes framework indexed by graph-valued interventions.

</details>

</div>

---

# Applications

<div class="paper-entry" markdown="1">

### Navigating the Divide: How Unattached Voters Respond to Politically Sponsored Protests in Polarized Contexts

<span class="paper-coauthors">with <a href="https://laurachelidonopoulos.github.io/">Laura Chelidonopoulos</a></span>
<span class="paper-status">Working Paper</span>

We combine elite interviews with a large-scale repeated-measures experiment to study how partisan-organized demonstrations shape political behavior. Politicians' elicited beliefs about voter responsiveness are used to pre-register hypotheses, which are then tested in a nationally representative survey experiment, enabling a direct comparison between elite expectations and observed behavioral responses.

</div>

<div class="paper-entry" markdown="1">

### When Coups Fail: Causal Estimates of Economic Decline after Unsuccessful Seizures of Power

<span class="paper-status">Working Paper</span>

Using a global dataset of unsuccessful coup attempts and matched counterfactual trajectories, I show that even failed coups generate substantive economic disruptions — including declines in investment, slower growth, and elevated political risk — highlighting how attempted regime change reshapes macroeconomic conditions even when it does not succeed.

</div>

<div class="paper-entry" markdown="1">

### Can the Resource Curse Be Avoided? Assessing the Impact of a Major Oil Field Discovery on Political Participation

<span class="paper-coauthors">with <a href="https://laurachelidonopoulos.github.io/">Laura Chelidonopoulos</a></span>
<span class="paper-status">Work in Progress</span>

We study how a sudden offshore oil discovery and the associated revenue windfall for nearby coastal municipalities shapes voter turnout, mobilization, and engagement with local politics.

</div>
