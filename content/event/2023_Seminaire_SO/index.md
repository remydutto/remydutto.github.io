---
title: Séminaire Statistique et Optimisation de l'Institut de Mathématiques de Toulouse

event: Séminaire Statistique et Optimisation de l'Institut de Mathématiques de Toulouse
event_url: https://indico.math.cnrs.fr/category/474/

location: Toulouse, France

summary: Méthode de contrôle optimal à deux niveaux et application
abstract: 'Le principe du maximum de Pontryagin fournit des conditions nécessaires d’optimalité pour des problèmes de commande optimale. Cependant, pour certaines applications industrielles, plus précisément sur des temps longs, la méthode classique de résolution de ces conditions nécessaires (méthode de tir) peut avoir des problèmes de convergence et/ou être trop coûteuse en temps pour être utilisée dans une solution embarquée. \

\

La méthode proposée pour y remédier est basée sur une formulation à deux niveaux du problème de commande optimale. Nous établissons un lien fort entre cette nouvelle approche et la méthode de tir multiple en utilisant la relation entre les co-états et la fonction valeur de Bellman. Nous profitons de cette formulation bi-niveaux pour introduire des approximations des fonctions valeurs par des réseaux de neurones afin d’accélérer le processus de résolution. En effet, cette approximation permet de transformer le problème de commande optimale à deux niveaux en un problème d’optimisation en dimension finie (Macro) et un ensemble de problèmes de commande optimale indépendants sur des intervalles de temps plus courts (Micro). \

\

Cette méthode sera appliquée au problème de répartition de couple d’un véhicule hybride sur le cycle de référence WLTC (Worldwide harmonized Light vehicles Test Cycles). L’objectif est de minimiser la consommation en carburant tout en imposant un état de charge final de batterie fixé. La méthode proposée sera comparée à la méthode de tir simple en termes d’optimalité et de temps de calcul.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-11-28'
date_end: #
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-04-08'

authors: 
- Olivier Cots
- Rémy Dutto
- Olivier Flebus
- Sophie Jan
- Serge Laporte
- Mariano Sans


tags:
- Optimal control
- Bilevel optimal control
- Neural network
- Indirect shooting

# Is this a featured talk? (true/false)
featured: false
url_code: ''
url_pdf: uploads/2023_Seminaire_SO.pdf
url_slides: ''
url_video: ''
---