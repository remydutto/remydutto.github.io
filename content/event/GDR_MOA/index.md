---
title: Journées annuelles 2023 du GdR MOA

event: Journées annuelles 2023 du GdR MOA
event_url: https://gdrmoa.math.cnrs.fr/journees-annuelles-2023-du-gdr-moa/

location: Perpignan, France 

summary: Méthode de contrôle optimal à deux niveaux et son application à la répartition du couple dans un véhicule hybride
abstract: 'Le principe du maximum de Pontryagin fournit des conditions n ́ecessaires d’optimalit ́e
pour des probl`emes de commande optimale en introduisant un co-vecteur associ ́ee `a l’ ́etat, ap-
pel ́e co- ́etat. En effet, la trajectoire d’ ́etat optimale doit ˆetre trouv ́ee parmi les projections des
trajectoires en  ́etat et co- ́etat, appel ́ees extr ́emales, donn ́ees par le principe du maximum.
`A partir d’une paire  ́etat et co- ́etat initiale, il est possible, sous certaines hypoth`eses, de con-
struire l’extr ́emale associ ́ee par int ́egration de la dynamique hamiltonienne. L’objectif de la
m ́ethode indirecte de tir est donc de rechercher le co- ́etat au temps initial, et m`ene au calcul
d’un z ́ero de la fonction de tir simple, ce qui est habituellement fait en utilisant un solveur de
type Newton. La fonction de tir simple est connue pour ˆetre sensible `a la condition initiale. De
plus, une bonne initialisation doit ˆetre donn ́ee pour s’assurer que le solveur converge.
On propose une m ́ethode de pr ́econditionnement de la fonction de tir [1], bas ́ee d’une part sur une
interpr ́etation g ́eom ́etrique du co- ́etat en lien avec l’ensemble accessible du syst`eme augment ́e, et
d’autre part sur la transform ́ee de Mathieu qui fournit un changement de variables dans l’espace
des phases `a partir d’un diff ́eomorphisme sur l’ ́etat.
On applique cette nouvelle m ́ethode sur le probl`eme de r ́epartition de couple d’un v ́ehicule
hybride  ́electrique. Le pr ́econditionnement est construit `a partir d’une transformation lin ́eaire
d’une ellipse en un cercle. On montre num ́eriquement que cette m ́ethode permet de r ́eduire le
nombre d’it ́erations de notre solveur. De plus, dans nos exp ́eriences, il est pr ́ef ́erable d’utiliser
le pr ́econditionnement plutˆot que d’avoir une bonne initialisation de la fonction de tir obtenue
`a partir d’une approximation de la fonction valeur [2].'

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