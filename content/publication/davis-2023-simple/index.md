---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A simple and powerful framework for stable dynamic network embedding
subtitle: ''
summary: ''
authors:
- Ed Davis
- Ian Gallagher
- Daniel Lawson
- Patrick Rubin-Delanchy
tags: []
categories: []
date: '2022-01-01'
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
abstract: 'In this paper, we address the problem of dynamic network embedding, that is, representing the nodes of a dynamic network as evolving vectors within a low-dimensional space. While the field of static network embedding is wide and established, the field of dynamic network embedding is comparatively in its infancy. We propose that a wide class of established static network embedding methods can be used to produce interpretable and powerful dynamic network embeddings when they are applied to the dilated unfolded adjacency matrix. We provide a theoretical guarantee that, regardless of embedding dimension, these unfolded methods will produce stable embeddings, meaning that nodes with identical latent behaviour will be exchangeable, regardless of their position in time or space. We additionally define a hypothesis testing framework which can be used to evaluate the quality of a dynamic network embedding by testing for planted structure in simulated networks. Using this, we demonstrate that, even in trivial cases, unstable methods are often either conservative or encode incorrect structure. In contrast, we demonstrate that our suite of stable unfolded methods are not only more interpretable but also more powerful in comparison to their unstable counterparts.'
publication: '[arXiv preprint](https://arxiv.org/abs/2311.09251)'
---
