---
title: Geometric preconditioner for indirect method and application

event: SMAI MODE 2024
event_url: https://indico.math.cnrs.fr/event/9418/

location: Lyon 
address:
  street: 450 Serra Mall
  city: Stanford
  region: CA
  postcode: '94305'
  country: United States

summary: SMAI MODE 2024 
abstract: 'Le principe du maximum de Pontryagin fournit des conditions nécessaires d’optimalité pour des problèmes de commande optimale en introduisant un co-vecteur associée à l’état, appelé co-état. En effet, la trajectoire d’état optimale doit être trouvée parmi les projections des trajectoires en état et co-état, appelées extrémales, données par le principe du maximum.
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
date: '2030-06-01T13:00:00Z'
date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
