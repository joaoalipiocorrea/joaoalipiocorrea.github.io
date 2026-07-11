---
layout: clean
title: "Research"
permalink: /research/
---

# Research

<h2 class="group">Methods</h2>

<div class="paper">
  <h3>Sharp Closed-Form Bounds for Interference Contamination in Linear ATT Designs</h3>
  <p class="teaser">Derives sharp, closed-form bounds on the bias that interference injects into any linear ATT estimator, using a doubly robust estimate of the average spillover and a width that grows with how concentrated the weights are.</p>
  <input type="checkbox" id="s1" class="toggle">
  <div class="actions">
    <a class="btn" href="/files/Alipio-Correa_Sharp-Closed-Form-Bounds-for-Interference-Contamination-in-Linear-ATT-Designs.pdf">Paper</a>
    <a class="btn" href="/files/Alipio-Correa_Sharp-Closed-Form-Bounds-for-Interference-Contamination-in-Linear-ATT-Designs_Supplement.pdf">Supplement</a>
    <a class="btn" href="/files/Alipio-Correa_Poster_Sharp-Bounds-Interference.pdf">Poster</a>
    <label for="s1" class="btn">Summary</label>
  </div>
  <div class="more"><p class="abstract">Workhorse estimators of the treatment effect on the treated, from difference-in-differences to synthetic control, build their counterfactual from control-unit outcomes, and they break down when the treatment spills over onto those controls, which contaminates the counterfactual and biases the estimate by an unknown amount. I develop a framework that detects this spillover contamination and bounds how large it can be rather than assuming it away. A doubly robust step recovers the average spillover among exposed controls under an exposure-ignorability condition, and that restriction yields sharp, closed-form partial-identification bounds on the bias of any linear estimator, with a width governed by how concentrated its weights are. Uniform-weight difference-in-differences point-identifies the contamination once the average spillover is known, while synthetic control and other concentrated-weight designs face genuine partial identification, and I pair the bounds with Imbens-Manski inference, sensitivity analysis, and two applications to Brazilian electoral politics.</p></div>
</div>

<div class="paper">
  <h3>Synthetic Control Under Interference: Detecting and Correcting Bias</h3>
  <p class="teaser">Shows that spillovers onto donors bias synthetic control in proportion to the weight on exposed units, and builds a randomization test and weight corrections that detect and remove it.</p>
  <input type="checkbox" id="s2" class="toggle">
  <div class="actions">
    <a class="btn" href="/files/Alipio-Correa_Synthetic-Control-Method-under-Interference.pdf">Paper</a>
    <label for="s2" class="btn">Summary</label>
  </div>
  <div class="more"><p class="abstract">Synthetic control estimates a policy's effect by comparing the treated unit to a weighted average of untreated donors, and it is credible only under SUTVA, when the policy leaves those donor units untouched. This paper shows that once spillovers reach the donors, the resulting bias is governed entirely by how much weight the estimator places on the exposed units. I turn that result into a finite-sample exact randomization test that screens for interference before estimation, and corrections that reshape the donor weights toward safer, less exposed units and remove the bias using only pre-treatment information. In several well-known studies these tools confirm the credibility of some designs and uncover, in others, spillovers that standard practice would miss and that meaningfully change the reported conclusions.</p></div>
</div>

<div class="paper">
  <h3>Efficient Semiparametric Inference for Interventions on Network Structure</h3>
  <p class="teaser">Develops semiparametric efficiency theory for intervening on the network itself, deriving the efficient influence function and a cross-fitted, doubly robust estimator for how outcomes change under a counterfactual graph.</p>
  <input type="checkbox" id="s3" class="toggle">
  <div class="actions">
    <label for="s3" class="btn">Summary</label>
  </div>
  <div class="more"><p class="abstract">Many questions in the social sciences are really questions about the network itself: what would happen to legislators' output if cross-party ties were more common, or to local violence if administrative boundaries were drawn differently. I develop semiparametric efficiency theory for the structural average direct effect, which measures the average change in units' outcomes when the observed network is replaced by a counterfactual version produced by a graph-shift operator. Under a shared-state model of interference, I show this target is pathwise differentiable and derive its efficient influence function, which yields a cross-fitted, doubly robust estimator that is root-n consistent and semiparametrically efficient. I extend the framework with an operator class whose correction term has a closed form and a distance-indexed decomposition that attributes the effect to network neighborhoods at increasing distance, with two motivating applications, party rewiring in the 117th U.S. Congress and counterfactual administrative boundaries in Nigerian conflict diffusion.</p></div>
</div>

<h2 class="group">Applications</h2>

<div class="paper">
  <h3>Can the Resource Curse be Avoided? Assessing the Impact of a Major Oil Field Discovery on Political Participation <span class="authors">(with <a href="https://laurachelidonopoulos.github.io/">Laura Chelidonopoulos</a>)</span></h3>
  <p class="teaser">Investigates whether a mature democracy can absorb a sudden offshore-oil windfall without the political damage seen in fragile states, using original geolocated data on extraction and municipal revenue.</p>
  <input type="checkbox" id="s4" class="toggle">
  <div class="actions">
    <label for="s4" class="btn">Summary</label>
  </div>
  <div class="more"><p class="abstract">The resource curse has mostly been documented in fragile and authoritarian states. This paper asks whether a mature democracy can absorb a sudden oil windfall without paying the same political price. We assemble original geolocated data on daily offshore oil extraction and the revenue it sends to nearby coastal municipalities, and we link the timing of each windfall to voter turnout, political mobilization, and engagement with local government. Together, the data support a high-frequency, municipality-level test of whether democratic institutions can blunt the resource curse.</p></div>
</div>

<div class="paper">
  <h3>Diverging at Fifteen: How Early Educational Sorting Shapes Far-Right Voting in France <span class="authors">(with Joao P Freitas Gomes and <a href="https://laurachelidonopoulos.github.io/">Laura Chelidonopoulos</a>)</span></h3>
  <p class="teaser">Argues that France's early sorting of adolescents into academic and vocational tracks is an unrecognized driver of the far-right vote, tracing tracked cohorts to how they later vote.</p>
  <input type="checkbox" id="s5" class="toggle">
  <div class="actions">
    <label for="s5" class="btn">Summary</label>
  </div>
  <div class="more"><p class="abstract">How a state sorts its children in school can shape how they vote decades later. We argue that the educational tracks into which France sorts its adolescents, academic for some and vocational for others, are a powerful and largely unrecognized source of the far-right vote. Assignment to the vocational track, which follows social class as much as talent, channels young people into the jobs most exposed to competition from immigrant labor, and through that exposure, real or merely feared, toward the far right, both when they first become eligible and again once they are working. The larger claim is that the state helps produce its own opposition, and that class divisions formalized in the classroom resurface as the grievances the far right mobilizes. We match the state's own records of who was tracked where to how entire cohorts later vote, down to the single polling station.</p></div>
</div>

<div class="paper">
  <h3>Navigating the Divide: How Unattached Voters Respond to Politically Sponsored Protests in Polarized Contexts <span class="authors">(with <a href="https://laurachelidonopoulos.github.io/">Laura Chelidonopoulos</a>)</span></h3>
  <p class="teaser">Pairs elite interviews with a large survey experiment to compare politicians' beliefs about how unattached voters respond to party-sponsored protests with how they actually respond.</p>
  <input type="checkbox" id="s6" class="toggle">
  <div class="actions">
    <label for="s6" class="btn">Summary</label>
  </div>
  <div class="more"><p class="abstract">We combine elite interviews with a large-scale repeated-measures experiment to study how partisan-organized demonstrations shape political behavior. Politicians' elicited beliefs about voter responsiveness are used to pre-register hypotheses, which are then tested in a nationally representative survey experiment, enabling a direct comparison between elite expectations and observed behavioral responses.</p></div>
</div>
