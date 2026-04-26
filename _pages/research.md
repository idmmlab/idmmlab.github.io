---
layout: page
title: Research
permalink: /research/
description: Our work spans three intertwined research directions.
nav: true
nav_order: 3
---

The IDMM Lab develops computational frameworks that connect **design**,
**physics**, and **manufacturing**. We treat the manufacturing process
as a first-class design variable: rather than designing a part and
then figuring out how to build it, we co-design the geometry, the
material, and the process together. Our work spans three intertwined
directions.

---

## 1. Generative Design for Engineering Systems

Modern engineering systems — from aerospace structures to
high-performance heat exchangers — live in design spaces far too
large for human intuition alone. We develop **generative models**
(diffusion models, GFlowNets, and physics-informed generative
networks) that propose novel geometries and microstructures
satisfying multiple physical and manufacturing constraints at once.

**Current questions we are asking:**
- How do we embed manufacturing constraints directly into generative
  priors, so the model proposes *makeable* designs from the start?
- How do we combine generative design with multi-fidelity physics
  evaluators to accelerate candidate screening?
- How do we expose the trade-off frontier (weight vs. stiffness vs.
  buildability) as a navigable design space, not a single point?

---

## 2. Advanced Manufacturing — Metal Additive Manufacturing

Metal additive manufacturing (AM) is enormously capable and
enormously temperamental. Melt-pool dynamics, residual stress,
microstructure evolution, and part-scale distortion are all coupled
across many orders of length and time scale. We build **process-aware
models** of metal AM that capture this coupling, and use them to
qualify, control, and optimize builds.

**Current directions:**
- Data-driven surrogates for melt-pool and microstructure prediction,
  trained on high-fidelity CFD and phase-field simulations.
- Process parameter optimization for quality, productivity, and
  sustainability under uncertainty.
- Design-for-AM: feedback loops between generative design and
  process qualification.

---

## 3. Multiphysics Simulation &amp; Digital Twins

Simulation is only useful when it is fast, trusted, and connected to
the real process. We develop **multiscale, multiphysics simulation
frameworks** — thermal, mechanical, metallurgical — and couple them
with learned surrogates to form **digital twins** of manufacturing
processes. Our twins support predictive quality, closed-loop control,
and what-if exploration for process engineers.

**Current directions:**
- Hybrid models that combine first-principles physics with learned
  components (residual learning, operator networks).
- Online assimilation of sensor data (thermal imaging, acoustic
  monitoring) into the digital twin.
- Uncertainty quantification and reliability for safety-critical
  AM parts.

---

## Funding &amp; Collaborators

*This section will list active grants and academic / industrial
collaborators as projects come online.*
