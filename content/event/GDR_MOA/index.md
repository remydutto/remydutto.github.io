---
title: Journées annuelles 2023 du GdR MOA

event: Journées annuelles 2023 du GdR MOA
event_url: https://gdrmoa.math.cnrs.fr/journees-annuelles-2023-du-gdr-moa/

location: Perpignan, France 

summary: Méthode de contrôle optimal à deux niveaux et son application à la répartition du couple dans un véhicule hybride
abstract: 'Le principe du maximum de Pontryagin fournit des conditions n ́ecessaires d’optimalit ́e
pour des probl`emes de commande optimale. Cependant, pour certaines applications indus-
trielles, plus pr ́ecis ́ement sur des temps longs, la m ́ethode classique de r ́esolution de ces condi-
tions n ́ecessaires (m ́ethode de tir) peut avoir des probl`emes de convergence [2] et/ou ˆetre trop
coˆuteuse en temps pour ˆetre utilis ́ee dans une solution embarqu ́ee.
La m ́ethode propos ́ee pour y rem ́edier est bas ́ee sur une formulation `a deux niveaux du probl`eme
de commande optimale. Nous  ́etablissons un lien fort entre cette nouvelle approche et la m ́ethode
de tir multiple en utilisant la relation entre les co- ́etats et la fonction valeur de Bellman [1].
Nous profitons de cette formulation bi-niveaux pour introduire des approximations des fonc-
tions valeurs de Bellman par des r ́eseaux de neurones afin d’acc ́el ́erer le processus de r ́esolution.
En effet, cette approximation permet de transformer le probl`eme de commande optimale `a
deux niveaux en un probl`eme d’optimisation en dimension faible (M acro) et un ensemble
de probl`emes de commande optimale ind ́ependants sur des intervalles de temps plus courts
(M icro).
Cette m ́ethode sera appliqu ́ee au probl`eme de r ́epartition de couple d’un v ́ehicule hybride sur le
cycle de r ́ef ́erence WLTC (Worldwide harmonized Light vehicles Test Cycles). L’objectif est de
minimiser la consommation en carburant tout en imposant un  ́etat de charge final de batterie
fix ́e. La m ́ethode propos ́ee sera compar ́ee `a la m ́ethode de tir simple en terme d’optimalit ́e et
de temps de calcul.'

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