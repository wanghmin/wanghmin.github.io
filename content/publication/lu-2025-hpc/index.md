---
title: High-performance CPU Cloth Simulation Using Domain-decomposed Projective Dynamics
authors:
- Zixuan Lu
- Ziheng Liu
- Lei Lan
- admin
- Yuko Ishiwaka
- Chenfanfu Jiang
- Kui Wu
- Yin Yang
date: '2025-07-01'
publishDate: '2025-10-10T08:37:01.278987Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH), 44*(4)'

abstract: Whenever the concept of high-performance cloth simulation is brought up,
  GPU acceleration is almost always the first that comes to mind. Leveraging immense
  parallelization, GPU algorithms have demonstrated significant success recently,
  whereas CPU methods are somewhat overlooked. Indeed, the need for an efficient CPU
  simulator is evident and pressing. In many scenarios, high-end GPUs may be unavailable
  or are already allocated to other tasks, such as rendering and shading. A high-performance
  CPU alternative can greatly boost the overall system capability and user experience.
  Inspired by this demand, this paper proposes a CPU algorithm for high-resolution
  cloth simulation. By partitioning the garment model into multiple (but not massive)
  sub-meshes or domains, we assign per-domain computations to individual CPU processors.
  Borrowing the idea of projective dynamics that breaks the computation into global
  and local steps, our key contribution is a new parallelization paradigm at domains
  for both global and local steps so that domain-level calculations are sequential
  and lightweight. The CPU has much fewer processing units than a GPU. Our algorithm
  mitigates this disadvantage by wisely balancing the scale of the parallelization
  and convergence. We validate our method in a wide range of simulation problems involving
  high-resolution garment models. Performance-wise, our method is at least one order
  faster than existing CPU methods, and it delivers a similar performance compared
  with the state-of-the-art GPU algorithms in many examples, but without using a GPU.
tags:
- cloth simulation
- parallel computation
- GPU algorithm
- CPU algorithm
links:
- name: Page
  url: https://sig25ddmpd.github.io/
url_video: https://drive.google.com/file/d/1kafSWDTJ8wiSvPrt9c3MaYG8Y6gysooF/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/JTSIoMnVPJ0?si=53hYxUenAEF1rAKn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?isOutside=true&aid=115349181697830&bvid=BV1kY4Jz1E1c&cid=32966837495&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
