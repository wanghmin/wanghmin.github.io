---
title: Incremental Deformation Subspace Reconstruction
authors:
- Rajaditya Mukherjee
- Xiaofeng Wu
- admin
date: '2016-10-11'
publishDate: '2024-03-03T02:42:26.938077Z'
publication_types:
- article-journal
publication: '*Computer Graphics Forum (Pacific Graphics), 35*(7)'

abstract: Recalculating the subspace basis of a deformable body is a mandatory
  procedure for subspace simulation, after the body gets modified by interactive applications.
  However, using linear modal analysis to calculate the basis from scratch is known
  to be computationally expensive. In the paper, we show that the subspace of a modified
  body can be efficiently obtained from the subspace of its original version, if mesh
  changes are small. Our basic idea is to approximate the stiffness matrix by its
  low-frequency component, so we can calculate new linear deformation modes by solving
  an incremental eigenvalue decomposition problem. To further handle nonlinear deformations
  in the subspace, we present a hybrid approach to calculate modal derivatives from
  both new and original linear modes. Finally, we demonstrate that the cubature samples
  trained for the original mesh can be reused in fast reduced force and stiffness
  matrix evaluation, and we explore the use of our techniques in various simulation
  problems. Our experiment shows that the updated subspace basis still allows a simulator
  to generate visual plausible deformation effects. The whole system is efficient
  and it is compatible with other subspace construction approaches.
summary: In the paper, we show that the deformation subspace of a modified
  body can be efficiently obtained from the subspace of its original version, if mesh
  changes are small.
tags:
- 'I.3.7 Computer Graphics: Three-Dimensional Graphics and Realism—Animation'
links:
url_video: https://drive.google.com/file/d/16XlWmrVgMCZdGiIn5c8xetjOo8QW1YaQ/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/SuzV_rpSOfY?si=-yiT0V0UEau0iNdH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=552833148&bvid=BV1ui4y1X77c&cid=563614344&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
