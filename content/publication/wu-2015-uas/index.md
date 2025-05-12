---
title: A Unified Approach for Subspace Simulation of Deformable Bodies in Multiple
  Domains
authors:
- Xiaofeng Wu
- Rajaditya Mukherjee
- admin
date: '2015-11-01'
publishDate: '2024-03-03T02:42:26.901447Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia), 34*(6)'

abstract: Multi-domain subspace simulation can efficiently and conveniently simulate
  the deformation of a large deformable body, by constraining the deformation of each
  domain into a different subspace. The key challenge in implementing this method
  is how to handle the coupling among multiple deformable domains, so that the overall
  effect is free of gap or locking issues. In this paper, we present a new domain
  decomposition framework that connects two disjoint domains through coupling elements.
  Under this framework, we present a unified simulation system that solves subspace
  deformations and rigid motions of all of the domains by a single linear solve. Since
  the coupling elements are part of the deformable body, their elastic properties
  are the same as the rest of the body and our system does not need stiffness parameter
  tuning. To quickly evaluate the reduced elastic forces and their Jacobian matrices
  caused by the coupling elements, we further develop two cubature optimization schemes
  using uniform and non-uniform cubature weights. Our experiment shows that the whole
  system can efficiently handle large and complex scenes, many of which cannot be
  easily simulated by previous techniques without limitations.
summary: 'We present a domain
  decomposition framework that connects two disjoint domains through coupling elements.
  Under this framework, we present a unified system that solves subspace
  deformations and rigid motions of all of the domains by a single linear solve.'
tags:
- cubature approximation
- domain decomposition
- finite element method
- nonlinear elasticity
- subspace simulation
links:
url_video: https://drive.google.com/file/d/1DVhY-O05Goup4TYZfcUDo_kKvSDZ1ozI/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/9zzbeAR0i_8?si=O7vLFWnTgIHGK85T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=212813695&bvid=BV1ha41147Qs&cid=563649196&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
