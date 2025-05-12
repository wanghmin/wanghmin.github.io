---
title: A GPU-Based Multilevel Additive Schwarz Preconditioner for Cloth and Deformable
  Body Simulation
authors:
- Botao Wu
- Zhendong Wang
- admin
date: '2022-07-01'
publishDate: '2024-03-03T02:42:27.050540Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH), 41*(4)'

abstract: In this paper, we wish to push the limit of real-time cloth and deformable
  body simulation to a higher level with 50K to 500K vertices, based on the development
  of a novel GPU-based multilevel additive Schwarz (MAS) pre-conditioner. Similar
  to other preconditioners under the MAS framework, our preconditioner naturally adopts
  multilevel and domain decomposition concepts. But contrary to previous works, we
  advocate the use of small, non-overlapping domains that can well explore the parallel
  computing power on a GPU. Based on this idea, we investigate and invent a series
  of algorithms for our preconditioner, including multilevel domain construction using
  Morton codes, low-cost matrix precomputation by one-way Gauss-Jordan elimination,
  and conflict-free symmetric-matrix-vector multiplication in runtime preconditioning.
  The experiment shows that our preconditioner is effective, fast, cheap to precompute
  and scalable with respect to stiffness and problem size. It is compatible with many
  linear and nonlinear solvers used in cloth and deformable body simulation with dynamic
  contacts, such as PCG, accelerated gradient descent and L-BFGS. On a GPU, our preconditioner
  speeds up a PCG solver by approximately a factor of four, and its CPU version outperforms
  a number of competitors, including ILU0 and ILUT.
summary: 'In this paper, we wish to push the limit of real-time cloth and deformable
  body simulation to a higher level with 50K to 500K vertices, based on the development
  of a novel GPU-based multilevel additive Schwarz (MAS) pre-conditioner.'
featured: true
tags:
- preconditioning
- multilevel method
- conjugate gradient
- cloth and deformable body simulation
- additive Schwarz
links:
url_video: https://drive.google.com/file/d/12GlHD89J2MVbLJ0roCC-J0dD5PUSYkSW/view
url_code: publication/wu-2022-gbm/Wu-2022-GBM.zip
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/TH5g8TuKIkk?si=esqb7xKF4dvqRveA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=511687484&bvid=BV19u41167Ma&cid=724739537&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
