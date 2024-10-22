---
title: Geometric preconditioner for indirect shooting and application to hybrid vehicle
authors:
- Olivier Cots
- Rémy Dutto
- Sophie Jan
- Serge Laporte
author_notes:
- IRIT
- Vitesco Technologies, IRIT, IMT
- IMT
- IMT
date: '2024-02-01'
publishDate: '2024-04-06T16:25:30.448420Z'
publication_types: ['paper-conference']
# all publication_types : https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types 
publication: 4th IFAC Conference of Modelling, Identification and Control of Nonlinear Systems
publication_short: 4th IFAC MICNON Conference
abstract: 'In this article, we are interested in the hybrid electric vehicle torque split and gear shift problem, which can be formulated as a classical Lagrange optimal control problem with fixed initial condition. The Pontryagin maximum principle gives necessary optimality conditions adjoining to the state a covector called costate. Thus, the optimal state trajectory has to be found among the projections of the lifted trajectories, called Pontryagin extremals, given by the maximum principle. The indirect simple shooting method aims to compute Pontryagin extremals reducing the resolution to the research of the initial costate. Classically, a Newtonlike solver is used to compute zeros of the so-called shooting equations. The main drawback of this method is its sensitivity to the initial guess. Indeed, a good one needs to be given to make the Newton solver converge, which is not an easy task in practice. We propose a preconditioning method of the shooting function based on a geometrical interpretation of the costate, in relation with the reachable set of the extended system and the underlying symplectic structure. We numerically show that this method reduces the number of iterations of our solver. Remarkably, in our experiments, it is better to use the preconditioner than a clever initial guess for the Newton solver.'
tags:
- Pontryagin maximum principle
- Indirect shooting
- Geometric preconditioner
- Mathieu transformation
- Costate interpretation
- Hybrid electric vehicle
links:
- name: URL
  url: https://hal.science/hal-04473962
url_pdf: https://hal.science/hal-04473962v2/file/CDJL_IFAC_V2.pdf
---
