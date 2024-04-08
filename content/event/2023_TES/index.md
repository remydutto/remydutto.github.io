---
title: Thematic Einstein Semester 2023 conference on mathematical optimization for machine learning

event: Thematic Einstein Semester 2023 conference on mathematical optimization for machine learning
event_url: https://mathplus.de/topic-development-lab/tes-summer-2023/final-conference/

location: Berlin, Germany

summary: Bi-level optimal control method and its application to the hybrid electric vehicle torque split and gear shift problem
abstract: 'The Pontryagin’s maximum principle gives necessary conditions to optimal control problems. Nevertheless, for some industrial applications, especially when the integration time is long, the classical method used to solve these necessary conditions (indirect simple shooting) may have some numerical convergence issues and/or be too time consuming to be proposed on embedded solutions. \

\

The proposed method to overcome these issues is based on a bi-level decomposition of the studied optimal control problem. A strong link between this new approach and the indirect multiple shooting method is highlighted, by using the link between the Pontryagin co-states and the value functions. We exploit this bi-level formulation to approximate the value functions by neural networks, to speed up the embedded resolution. In fact, this approximation transforms the optimal control problem into a low-dimensional optimization problem, called (M acro), and N independent optimal control problems on smaller time intervals, called (Micro). \

\

This method is applied to the hybrid electric vehicle torque split and gear shift problem, on the Worldwide harmonized Light vehicle Test Cycle. The goal is to minimize the fuel consumption with a fixed initial and final state of charge of the battery. The proposed method is compared to the indirect simple shooting in terms of cost and computing time.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-10-18'
date_end: '2023-10-20'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-04-08'

authors: 
- Olivier Cots
- Rémy Dutto
- Sophie Jan
- Serge Laporte

tags:
- Optimal control
- Bilevel optimal control
- Neural network

# Is this a featured talk? (true/false)
featured: false
url_code: ''
url_pdf: uploads/2023_GDR_MOA.pdf
url_slides: ''
url_video: ''
---