---
title: Geometric preconditioner for indirect method and application

event: SMAI MODE 2024
event_url: https://indico.math.cnrs.fr/event/9418/

location: Lyon, France 

summary: SMAI MODE 2024 
abstract: 'Le principe du maximum de Pontryagin fournit des conditions nécessaires d’optimalité pour des problèmes de commande optimale en introduisant un co-vecteur associée à l’état, appelé co-état. En effet, la trajectoire d’état optimale doit être trouvée parmi les projections des trajectoires en état et co-état, appelées extrémales, donnes par le principe du maximum. \

À partir d’une paire état et co-état initiale, il est possible, sous certaines hypothèses, de construire l’extrémale associée par intégration de la dynamique hamiltonienne. L’objectif de la méthode indirecte de tir est donc de rechercher le co-état au temps initial, et mène au calcul d’un zéro de la fonction de tir simple, ce qui est habituellement fait en utilisant un solveur de type Newton. La fonction de tir simple est connue pour être sensible à la condition initiale. De plus, une bonne initialisation doit être donnée pour s’assurer que le solveur converge. \

On propose une méthode de préconditionnement de la fonction de tir [1], basée d’une part sur une interprétation géométrique du co-état en lien avec l’ensemble accessible du système augmenté, et d’autre part sur la transformée de Mathieu qui fournit un changement de variables dans l’espace des phases à partir d’un difféomorphisme sur l’ ́etat.
On applique cette nouvelle méthode sur le problème de répartition de couple d’un véhicule hybride électrique. Le préconditionnement est construit à partir d’une transformation linéaire d’une ellipse en un cercle. On montre numériquement que cette méthode permet de réduire le nombre d’itérations de notre solveur. De plus, dans nos expériences, il est préférable d’utiliser le préconditionnement plutôt que d’avoir une bonne initialisation de la fonction de tir obtenue à partir d’une approximation de la fonction valeur [2].

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-03-27'
date_end: '2024-03-29'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-04-07'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: uploads/Slides_SMAI_MODE_2024
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
