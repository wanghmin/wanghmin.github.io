---
title: Efficient GPU Cloth Simulation with Non-Distance Barriers and Subspace Reuse
authors:
- Lei Lan
- Zixuan Lu
- Jingyi Long
- Chun Yuan
- Xuan Li
- Xiaowei He
- admin
- Chenfanfu Jiang
- Yin Yang
date: '2024-12-03'
publishDate: '2024-10-14T09:55:39.574386Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia)*'

abstract: This paper pushes the performance of cloth simulation, making the simulation
  interactive even for high-resolution garment models while keeping every triangle
  untangled. The penetration-free guarantee is inspired by the interior point method,
  which converts the inequality constraints to barrier potentials. We propose a major
  overhaul of this modality within the projective dynamics framework by leveraging
  an adaptive weighting mechanism inspired by barrier formulation. This approach does
  not depend on the distance between mesh primitives, but on the virtual life span
  of a collision event and thus keeps all the vertices within feasible region. Such
  a non-distance barrier model allows a new way to integrate collision resolution into
  the simulation pipeline. Another contributor to the performance boost comes from
  the subspace reuse strategy. This is based on the observation that low-frequency
  strain propagation is near orthogonal to the deformation induced by collisions or
  self-collisions, often of high frequency. Subspace reuse then takes care of low-frequency
  residuals, while high-frequency residuals can also be effectively smoothed by GPU-based
  iterative solvers. We show that our method outperforms existing fast cloth simulators
  by at least one order while producing high-quality animations of high-resolution
  models.
tags:
- GPU simulation
- cloth animation
- collision detection
- parallel computation
summary: This paper pushes the performance of cloth simulation, making the simulation
  interactive even for high-resolution garment models while keeping every triangle
  untangled.
url_video: https://drive.google.com/file/d/1LF-Gz_vdIMG0kAVSuGiNc7NvGVjJtH9u/view?usp=sharing
---
<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/2ccqBMkSriA?si=gbCPraHMRBlbRIyz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?isOutside=true&aid=113309592323479&bvid=BV1upmnYvEqS&cid=26297630748&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
</p>
