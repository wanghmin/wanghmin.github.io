---
title: 'CAMA: Contact-Aware Matrix Assembly with Unified Collision Handling for GPU-Based
  Cloth Simulation'
authors:
- Min Tang
- admin
- Le Tang
- Ruofeng Tong
- Dinesh Manocha
date: '2016-05-01'
publishDate: '2024-03-03T02:42:26.924066Z'
publication_types:
- article-journal
publication: '*Computer Graphics Forum (Eurographics), 35*(2)'

abstract: We present a novel GPU-based approach to robustly and efficiently
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
summary: We present a novel GPU-based approach to robustly and efficiently
  simulate high-resolution and complexly layered cloth. The key component of our formulation
  is a parallelized matrix assembly algorithm.
links:
url_video: https://drive.google.com/file/d/1aE7qyKFddgc_uXYFWNpVj-IEPySOy5U0/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/9ZFk5gFkDeU?si=NboK7NTtHW9POWGn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=640330267&bvid=BV17Y4y1W7Bw&cid=563614346&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
