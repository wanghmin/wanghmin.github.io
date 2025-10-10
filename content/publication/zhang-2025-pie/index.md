---
title: Physics-inspired Estimation of Optimal Cloth Mesh Resolution
authors:
- Diyang Zhang
- Zhendong Wang
- Zegao Liu
- Xinming Pei
- Weiwei Xu
- admin
date: '2025-08-11'
publishDate: '2025-05-13T06:24:55.245276Z'
publication_types:
- paper-conference
publication: '*ACM SIGGRAPH 2025 Conference Papers*'

abstract: 'In this paper, we tackle an important yet often overlooked question: What
  is the optimal mesh resolution for cloth simulation, without relying on preliminary
  simulations? The optimal resolution should be sufficient to capture fine details
  of all potential wrinkles, while avoiding an unnecessarily high resolution that
  wastes computational time and memory on excessive vertices. This challenge stems
  from the complex nature of wrinkle distribution, which varies spatially, temporally,
  and anisotropically across different orientations. To address this, we propose a
  method to estimate the optimal cloth mesh resolution, based on two key factors:
  material stiffness and boundary conditions.   To determine the influence of material
  stiffness on wrinkle wavelength and amplitude, we apply the experimental theory
  presented by Cerda and Mahadevan [2003] to calculate the optimal mesh resolution
  for cloth fabrics. Similarly, for boundary conditions influencing local wrinkle
  formation, we use the same scaling law to determine the source resolution for stationary
  boundary conditions introduced by garment-making techniques such as shirring, folding,
  stitching, and down-filling, as well as predicted areas accounting for dynamic wrinkles
  introduced by collision compression caused by human motions. To ensure a smooth
  transition between different source resolutions, we apply another experimental theory
  from [Vandeparre et al. 2011] to compute the transition distance. A mesh sizing
  map is introduced to facilitate smooth transitions, ensuring precision in critical
  areas while maintaining efficiency in less important regions. Based on these sizing
  maps, triangular meshes with optimal resolution distribution are generated using
  Poisson sampling and Delaunay triangulation. The resulting method can not only enhance
  the realism and precision of cloth simulations but also support diverse application
  scenarios, making it a versatile solution for complex garment design.'
summary:  we propose a novel method to determine the optimal mesh resolution
  for cloth simulation, without running any preliminary simulations.
featured: true
tags:
- mesh resolution
- wrinkle wavelength
- material stiffness
links:
url_video: https://drive.google.com/file/d/1uFUiFCdFgzOE10Rl6pAPIZgCFRAuc1Cg/view?usp=sharing
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/XbMiDJY8zTM?si=sMtxnee_PObD_f3b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?isOutside=true&aid=114498996273590&bvid=BV1h97ZzVETW&cid=29936061694&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
