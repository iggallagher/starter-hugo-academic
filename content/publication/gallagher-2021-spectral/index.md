---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Spectral embedding for dynamic networks with stability guarantees
subtitle: ''
summary: ''
authors:
- Ian Gallagher
- Andrew Jones
- Patrick Rubin-Delanchy
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-07-17T17:23:37+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-07-17T16:23:37.457619Z'
publication_types:
- '2'
abstract: 'We consider the problem of embedding a dynamic network, to obtain time-evolving vector representations of each node, which can then be used to describe changes in behaviour of individual nodes, communities, or the entire graph. Given this open-ended remit, we argue that two types of stability in the spatio-temporal positioning of nodes are desirable: to assign the same position, up to noise, to nodes behaving similarly at a given time (cross-sectional stability) and a constant position, up to noise, to a single node behaving similarly across different times (longitudinal stability). Similarity in behaviour is defined formally using notions of exchangeability under a dynamic latent position network model. By showing how this model can be recast as a multilayer random dot product graph, we demonstrate that unfolded adjacency spectral embedding satisfies both stability conditions. We also show how two alternative methods, omnibus and independent spectral embedding, alternately lack one or the other form of stability.'
publication: '[*Advances in Neural Information Processing Systems*](https://arxiv.org/abs/2106.01282)'
---
