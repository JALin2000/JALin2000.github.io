---
title: "Learning Over-Relaxation Policies for ADMM with Convergence Guarantees"
collection: publications
category: preprints
permalink: /publication/2026-04-30-learning-over-relaxation-policies-for-admm
date: 2026-04-30
venue: "arXiv preprint"
authors: "<strong>Junan Lin</strong>, Paul J. Goulart, Luca Furieri"
paperurl: "https://arxiv.org/pdf/2604.26932"
citation: "<strong>Junan Lin</strong>, Paul J. Goulart, and Luca Furieri. Learning Over-Relaxation Policies for ADMM with Convergence Guarantees. <i>arXiv preprint</i>, 2026."
---

The Alternating Direction Method of Multipliers (ADMM) is a widely used method for structured convex optimization, and its practical performance depends strongly on the choice of penalty and relaxation parameters. Motivated by settings such as Model Predictive Control (MPC), where one repeatedly solves related optimization problems with fixed structure and changing parameter values, we propose learning online updates of the relaxation parameter to improve performance on problem classes of interest. This choice is computationally attractive in OSQP-like architectures, since adapting relaxation does not trigger the matrix refactorizations associated with penalty updates. We establish convergence guarantees for ADMM with time-varying penalty and relaxation parameters under mild assumptions, and show on benchmark quadratic programs that the resulting learned policies improve both iteration count and wall-clock time over baseline OSQP.
