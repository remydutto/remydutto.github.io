---
title: FGS Conference on Optimization 2024

event: FGS Conference on Optimization 2024
event_url: https://www.unioviedo.es/fgs2024/

location: Gijon, Spain

summary: Geometric preconditioner for indirect shooting and application to hybrid vehicle
abstract: 'We are interested in the hybrid electric vehicle torque split and gear shift problem, which can be formulated as a classical Lagrange optimal control problem with fixed initial condition. The Pontryagin’s maximum principle gives necessary optimality conditions adjoining to the state a covector called costate. Thus, the optimal state trajectory has to be found among the projections of the lifted trajectories, called Pontryagin extremals, given by the maximum principle. The indirect simple shooting method aims to compute Pontryagin extremals reducing the resolution to the research of the initial costate. 

\

Classically, a Newton-like solver is used to compute zeros of the so-called shooting equations. The main drawback of this method is its sensitivity to the initial guess. Therefore, a good initial guess need to be given to make the Newton solver converge, which is not an easy task in practice. 

\

We propose a preconditioning method of the shooting function based on two main results. The first one is a geometrical interpretation of the costate that connects the final costate of the augmented system to the normal cone of the reachable set of the augmented system. The second result is well known as the Mathieu transformation, which gives the lifted canonical diffeomorphism on state-costate space from a diffeomorphism on the state space, and is related to the underlying symplectic structure. 

\

For the considered application, we construct a preconditioner based on the affine transformation of an ellipse into the unit circle. We numerically show that the proposed preconditioning method reduces the number of iterations of our solver. Remarkably, in our experiments, it is better to use the preconditioner than to provide a good initial guess for the shooting function.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-06-18'
date_end: '2024-06-21'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-06-21'

authors: 
- Olivier Cots
- Rémy Dutto
- Olivier Flebus
- Sophie Jan
- Serge Laporte
- Mariano Sans


tags:
- Geometric preconditioner
- Costate interpretation
- Mathieu transformation
- Optimal control

# Is this a featured talk? (true/false)
featured: false
url_code: ''
url_pdf: uploads/2024_FGS.pdf
url_slides: ''
url_video: ''
---