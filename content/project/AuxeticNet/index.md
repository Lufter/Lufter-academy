---
title: Auxetic Networks
summary: Adapting pruning strategy to generate auxetic material.
tags:
- Computational Material
date: "2019-07-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Lufter
  focal_point: Smart

#links:
#- icon: twitter
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Adapting pruning strategy to generate auxetic material from the grometry of packed moleculars. This project was implemented on the Google Could Service(GCP) with 96-core CPUs. The auxetic samples were ment to be one of the types in my machine learning dataset. This idea is inspired by Reid *etal.* [Auxetic metamaterials from disordered networks](https://www.pnas.org/content/115/7/E1384).

What we have implemented:

＊　Implemented pruning protocol on 96 core CPUs to generate auxetic networks.

＊　Implemented a stochastic protocol to produce large scale homogenous microstructure datasets by two‑point correlation function.