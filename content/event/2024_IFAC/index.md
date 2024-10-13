---
title: 4th IFAC Conference of Modelling, Identification and Control of Nonlinear Systems

event: 4th IFAC Conference of Modelling, Identification and Control of Nonlinear Systems
event_url: https://conferences.ifac-control.org/micnon2024/

location: Lyon, France 

summary: Geometric preconditioner for indirect shooting and application to hybrid vehicle
abstract: 'In this article, we are interested in the hybrid electric vehicle torque split and gear shift problem, which can be formulated as a classical Lagrange optimal control problem with fixed initial condition. The Pontryagin maximum principle gives necessary optimality conditions adjoining to the state a covector called costate. Thus, the optimal state trajectory has to be found among the projections of the lifted trajectories, called Pontryagin extremals, given by the maximum principle. The indirect simple shooting method aims to compute Pontryagin extremals reducing the resolution to the research of the initial costate. Classically, a Newton-like solver is used to compute zeros of the so-called shooting equations. The main drawback of this method is its sensitivity to the initial guess. Therefore, a good initial guess need to be given to make the Newton solver converge, which is not an easy task in practice. We propose a preconditioning method of the shooting function based on a geometrical interpretation of the costate, in relation with the reachable set of the extended system and the underlying symplectic structure. We numerically show that this method reduces the number of iterations of our solver. Remarkably, in our experiments, it is better to use the preconditioner than to provide an approximation of the costate solution.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-09-04'
date_end: '2024-09-06'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-09-04'

authors: 
- Olivier Cots
- Rémy Dutto
- Sophie Jan
- Serge Laporte

tags:
- Pontryagin maximum principle
- Indirect shooting
- Geometric preconditioner
- Mathieu transformation
- Costate interpretation
- Hybrid electric vehicle

# Is this a featured talk? (true/false)
featured: false
url_code: ''
url_pdf: uploads/2024_IFAC.pdf
url_slides: ''
url_video: ''
---