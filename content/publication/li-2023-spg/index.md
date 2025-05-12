---
title: Subspace-Preconditioned GPU Projective Dynamics with Contact for Cloth Simulation
authors:
- Xuan Li
- Yu Fang
- Lei Lan
- admin
- Yin Yang
- Minchen Li
- Chenfanfu Jiang
date: '2023-12-12'
publishDate: '2024-03-03T02:42:27.088211Z'
publication_types:
- paper-conference
publication: '*SIGGRAPH Asia 2023 Conference Papers*'

abstract: We propose an efficient cloth simulation method that combines the merits
  of two drastically different numerical procedures, namely the subspace integration
  and parallelizable iterative relaxation. We show those two methods can be organically
  coupled within the framework of projective dynamics (PD), where both low- and high-frequency
  cloth motions are effectively and efficiently computed. Our method works seamlessly
  with the state-of-the-art contact handling algorithm, the incremental potential
  contact (IPC), to offer the non-penetration guarantee of the resulting animation.
  Our core ingredient centers around the utilization of subspace for the expedited
  convergence of Jacobi-PD. This involves solving the reduced global system and smartly
  employing its precomputed factorization. In addition, we incorporate a time-splitting
  strategy to handle the frictional self-contacts. Specifically, during the PD solve,
  we employ a quadratic proxy to approximate the contact barrier. The prefactorized
  subspace system matrix is exploited in a reduced-space LBFGS. The LBFGS method starts
  with the reduced system matrix of the rest shape as the initial Hessian approximation,
  incorporating contact information into the reduced system progressively, while the
  full-space Jacobi iteration captures high-frequency details. Furthermore, we address
  penetration issues through a penetration correction step. It minimizes an incremental
  potential without elasticity using Newton-PCG. Our method can be efficiently executed
  on modern GPUs. Experiments show significant performance improvements over existing
  GPU solvers for high-resolution cloth simulation.
summary: We propose an efficient cloth simulation method that combines the merits
  of two drastically different numerical procedures, namely the subspace integration
  and parallelizable iterative relaxation.
tags:
- domain decomposition
- projective dynamics
- quasi-Newton methods
- subspace
links:
url_video: https://drive.google.com/file/d/1m8dsocK1x2k4jylOZMrZ_mLOlcR9VZEj/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/32nTfLSGsMU?si=bkzURFGmMsFq-cY6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=321096711&bvid=BV1ww411q7xC&cid=1271228451&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
