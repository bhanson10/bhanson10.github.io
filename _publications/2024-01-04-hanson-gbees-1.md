---
title: "State Estimation of Chaotic Trajectories: A Higher-Dimensional, Grid-Based, Bayesian Approach to Uncertainty Propagation"
collection: publications
category: conferences
permalink: /publications/2024-01-04-hanson-gbees-1
excerpt: ''
date: 2024-01-04
venue: 'AIAA SCITECH 2024 Forum'
paperurl: 'http://bhanson10.github.io/files/2024_AAS_SFM_Slides.pdf'
citation: '<strong>Hanson, B.L.</strong>, Rosengren, A.J., Bewley, T.R.: State estimation of chaotic trajectories: A higher-dimensional, grid-based, Bayesian approach to uncertainty propagation. In: AIAA SCITECH 2024 Forum, p. 0426 (2024).'
---

Abstract: The current landscape of orbital uncertainty propagation methods inadequately addresses the state estimation problem for nonlinear systems. In relatively low-perturbed regimes, or when measurement updates are frequent, state estimation methods that assume Gaussian uncertainty are valid, and errors resulting from linearizing the dynamics about an estimate are negligible. However, as novel space mission design techniques begin to exploit the chaoticity of N-body dynamics to efficiently explore new regimes of space, the Gaussianity assumption is often violated, and linearization errors accumulate. Uncertainty propagation methods that do not assume Gaussianity or linearize about an estimate are computationally expensive. Moreover, both classes of methods often disregard epistemic uncertainty, or the uncertainty of the model. To address the current limitations of orbital uncertainty propagation, we introduce a higher-dimensional extension to an existing Bayesian estimation algorithm that efficiently propagates the probability distribution function of a state governed by nonlinear dynamics. By adjusting the computational architecture of the algorithm and considering the dynamics of the system, we scale the existing, three-dimensional technique with poor time complexity to an efficient, four-dimensional one. The result is a robust, second-order accurate, time-adaptive, explicit time-marching scheme with the capability of propagating uncertainty governed by chaotic, nonlinear dynamics.
