---
title: Journées annuelles 2023 du GdR MOA

event: Journées annuelles 2023 du GdR MOA
event_url: https://gdrmoa.math.cnrs.fr/journees-annuelles-2023-du-gdr-moa/

location: Perpignan, France 

summary: Méthode de contrôle optimal à deux niveaux et son application à la répartition du couple dans un véhicule hybride
abstract: 'Le principe du maximum de Pontryagin fournit des conditions nécessaires d’optimalité pour des problèmes de commande optimale en introduisant un co-vecteur associée à l’état, appelé co-état. En effet, la trajectoire d’état optimale doit être trouvée parmi les projections des trajectoires en état et co-état, appelées extrémales, données par le principe du maximum. \

À partir d’une paire état et co-état initiale, il est possible, sous certaines hypothèses, de construire l’extrémale associée par intégration de la dynamique hamiltonienne. L’objectif de la méthode indirecte de tir est donc de rechercher le co-état au temps initial, et mène au calcul d’un zéro de la fonction de tir simple, ce qui est habituellement fait en utilisant un solveur de type Newton. La fonction de tir simple est connue pour être sensible à la condition initiale. De plus, une bonne initialisation doit être donnée pour s’assurer que le solveur converge. \

On propose une méthode de préconditionnement de la fonction de tir, basée d’une part sur une interprétation géometrique du co-état en lien avec l’ensemble accessible du système augmenté, et d’autre part sur la transformée de Mathieu qui fournit un changement de variables dans l’espace des phases à partir d’un difféomorphisme sur l’état. \

On applique cette nouvelle méthode sur le problème de répartition de couple d’un véhicule hybride électrique. Le préconditionnement est construit à partir d’une transformation linéaire d’une ellipse en un cercle. On montre numériquement que cette méthode permet de réduire le nombre d’itérations de notre solveur. De plus, dans nos expériences, il est préferable d’utiliser le préconditionnement plutôt que d’avoir une bonne initialisation de la fonction de tir obtenue à partir d’une approximation de la fonction valeur.'

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
url_pdf: uploads/Slides_SMAI_MODE_2024.pdf
url_slides: ''
url_video: ''
---