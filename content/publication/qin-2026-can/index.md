---
title: 'CAN: A Curvature-Aware Nesterov Optimizer for Fast Elastic Simulation With Topological Changes'
authors:
- Yuxiong Qin
- admin
- Qingfu Zhang
- Zhongkai Zhang
date: '2026-04-06'
publishDate: '2026-06-16T00:00:00Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Visualization and Computer Graphics*'
abstract: >-
  Fast simulation of elastic bodies is fundamental to computer graphics, yet
  current leading methods have a key limitation: they require fixed mesh
  connectivity. Existing methods leverage this assumption to achieve high
  performance but fail during topological changes such as cutting, fracturing,
  or merging. We present CAN, a novel optimizer that fundamentally decouples
  simulation acceleration from mesh topology. CAN introduces two Hessian-free,
  curvature-aware components: a Curvature-Aware Momentum (CAM) scheme that
  prevents overshooting by adaptively decaying momentum based on local gradient
  variations, and a Curvature-Aware Line Search (CALS) that provides
  high-quality step sizes via efficient directional curvature approximations.
  Since CAN relies solely on per-vertex, historical information, it is
  inherently parallel and topology-agnostic. We demonstrate that CAN achieves
  superior convergence compared to prior works across a wide range of
  dynamic-topology scenarios without any precomputation tied to connectivity,
  establishing a new paradigm for robust and efficient physics-based animation.
summary: >-
  We present CAN, a curvature-aware Nesterov optimizer that enables fast
  elastic simulation with topological changes without relying on fixed mesh
  connectivity.
tags:
- elastic simulation
- GPU
- line search
- nesterov
- physics-based simulation
- topology change
links:
- name: Page
  url: https://ieeexplore.ieee.org/document/11474973
---
