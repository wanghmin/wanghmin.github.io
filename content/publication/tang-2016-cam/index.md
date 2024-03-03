---
title: 'CAMA: Contact-Aware Matrix Assembly with Unified Collision Handling for GPU-Based
  Cloth Simulation'
authors:
- Min Tang
- Huamin Wang
- Le Tang
- Ruofeng Tong
- Dinesh Manocha
date: '2016-05-01'
publishDate: '2024-03-03T02:42:26.924066Z'
publication_types:
- article-journal
publication: '*Computer Graphics Forum (Eurographics)*'
doi: https://doi.org/10.1111/cgf.12851
abstract: Abstract We present a novel GPU-based approach to robustly and efficiently
  simulate high-resolution and complexly layered cloth. The key component of our formulation
  is a parallelized matrix assembly algorithm that can quickly build a large and sparse
  matrix in a compressed format and accurately solve linear systems on GPUs. We also
  present a fast and integrated solution for parallel collision handling, including
  collision detection and response computations, which utilizes spatio-temporal coherence.
  We combine these algorithms as part of a new cloth simulation pipeline that incorporates
  contact forces into implicit time integration for collision avoidance. The entire
  pipeline is implemented on GPUs, and we evaluate its performance on complex benchmarks
  consisting of 100 – 300K triangles. In practice, our system takes a few seconds
  to simulate one frame of a complex cloth scene, which represents significant speedups
  over prior CPU and GPU-based cloth simulation systems.
links:
- name: URL
  url: https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.12851
---