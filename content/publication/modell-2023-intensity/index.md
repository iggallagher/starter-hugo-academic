---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Intensity profile projection: a framework for continuous-time representation learning for dynamic networks'
subtitle: ''
summary: ''
authors:
- Alex Modell
- Ian Gallagher
- Emma Ceccherini
- Nick Whiteley
- Patrick Rubin-Delanchy
tags: []
categories: []
date: '2023-01-01'
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
publishDate: '2022-07-17T16:23:37.630274Z'
publication_types:
- '2'
abstract: 'We present a new algorithmic framework, Intensity Profile Projection, for learning continuous-time representations of the nodes of a dynamic network, characterised by a node set and a collection of instantaneous interaction events which occur in continuous time. Our framework consists of three stages: estimating the intensity functions underlying the interactions between pairs of nodes, e.g. via kernel smoothing; learning a projection which minimises a notion of intensity reconstruction error; and inductively constructing evolving node representations via the learned projection. We show that our representations preserve the underlying structure of the network, and are temporally coherent, meaning that node representations can be meaningfully compared at different points in time. We develop estimation theory which elucidates the role of smoothing as a bias-variance trade-off, and shows how we can reduce smoothing as the signal-to-noise ratio increases on account of the algorithm borrowing strength across the network'
publication: '[arXiv preprint](https://arxiv.org/abs/2306.06155)'
---