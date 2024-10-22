---
title:  Méthode à deux niveaux et préconditionnement géométrique en contrôle optimal. Application au problème de répartition de couple des véhicules hybrides électriques.
authors:
- Rémy Dutto
author_notes: 
- Vitesco Technologies, IRIT, IMT
date: '2024-10-07'
# doi : ""
publishDate: '2024-10-07'
publication_types: ["thesis"]
# all publication_types : https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types 
# publication: ""
# publication_short: ""

abstract: 'Motivé par le problème industriel de répartition de couple dans les véhicules hybrides électriques, ce travail propose principalement deux nouvelles méthodes de résolution indirectes de problèmes de commande optimale. 

\

La première est la méthode Macro-Micro qui est basée sur une décomposition à deux niveaux du problème de commande optimale, faisant intervenir les fonctions valeur de Bellman de manière explicite à des temps préalablement fixés. Ces fonctions sont connues pour être assez difficile à construire. L’idée principale est d’approcher ces fonctions valeur par des réseaux de neurones, ce qui mène à une résolution hiérarchique d’un problème d’optimisation en dimension faible et d’un ensemble de problèmes de commande optimale définis sur des intervalles de temps plus courts. 

\

La seconde est une méthode de préconditionnement géométrique qui permet une résolution plus efficace du problème de commande optimale. Cette méthode, basée sur l’interprétation géométrique du co-état et sur la transformée de Mathieu, utilise un changement de variable linéaire à partir de la simple transformation d’une ellipse en cercle. 

\

Ces deux méthodes, bien que présentées séparément, peuvent être combinées et mènent à une résolution plus rapide, robuste et légère du problème de répartition de couple, permettant ainsi que de s’approcher des critères d’embarquabilités.'

tags:
- Bilevel optimal control
- Geometric preconditioner
- Indirect shooting
- Pontryagin maximum principle
- Neural Network
- Hybrid electric vehicle

url_pdf: uploads/2024_PhD.pdf
---
