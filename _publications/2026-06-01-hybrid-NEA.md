---
title: "Autonomous Hybrid State Estimation in the Perturbed Two-Body System"
collection: publications
category: conferences
permalink: /publications/2026-06-01-hybrid-NEA
excerpt: ''
date: 2026-06-01
venue: '30th International Symposium on Space Flight Dynamics'
paperurl: 'https://www.researchgate.net/publication/406402905_Autonomous_Hybrid_State_Estimation_in_the_Perturbed_Two-Body_System'
citation: '<strong>Hanson, B.L.</strong>, Bewley, T.R., Rosengren, A.J.: Autonomous Hybrid State Estimation in the Perturbed Two-Body System. In: 30th International Symposium on Space Flight Dynamics, (2026)'
---

Abstract: The state uncertainty of an orbiting trajectory in the perturbed two-body system tends to oscillate between near-Gaussian and strongly non-Gaussian over the orbit. Hybrid estimators leverage this behavior by employing moment-based filters during the former and sample-based filters during the latter. Sample-based filters are more accurate than moment filters when uncertainty becomes highly non-Gaussian, but are computationally unwarranted otherwise. As a result, sample-based filters have been underutilized for impact probability prediction and spacecraft navigation. A hybrid filter addresses this limitation, but its performance hinges on the mechanism that controls the transitions between the two frameworks. A correlation exists between the normalized Euclidean distance, a moment-based metric of skew, and the Henze-Zirkler statistic, a sample-based measure of Gaussianity, in the two-body system that can be exploited to predict this transition. Herein, using a large set of near-Earth asteroid trajectories with varying geometries, a similarly strong relationship is confirmed to exist for the perturbed two-body system. With the derived transition boundary, the autonomous hybrid unscented Kalman filter/ensemble Gaussian mixture filter is applied to the state estimation of two high-fidelity trajectories: 2024 YR4, an Apollo-type asteroid, and the Parker Solar Probe, an artificial satellite. These cases show that the hybrid framework is an efficient, accurate alternative to its constituent filters.