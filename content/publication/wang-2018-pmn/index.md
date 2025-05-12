---
title: Parallel Multigrid for Nonlinear Cloth Simulation
authors:
- Zhendong Wang
- Longhua Wu
- Marco Fratarcangeli
- Min Tang
- admin
date: '2018-10-01'
publishDate: '2024-03-03T02:42:26.975107Z'
publication_types:
- article-journal
publication: '*Computer Graphics Forum (Pacific Graphics, best paper award), 37*(7)'

abstract: Accurate high-resolution simulation of cloth is a highly desired
  computational tool in graphics applications. As single-resolution simulation starts
  to reach the limit of computational power, we believe the future of cloth simulation
  is in multi-resolution simulation. In this paper, we explore nonlinearity, adaptive
  smoothing, and parallelization under a full multigrid (FMG) framework. The foundation
  of this research is a novel nonlinear FMG method for unstructured meshes. To introduce
  nonlinearity into FMG, we propose to formulate the smoothing process at each resolution
  level as the computation of a search direction for the original high-resolution
  nonlinear optimization problem. We prove that our nonlinear FMG is guaranteed to
  converge under various conditions and we investigate the improvements to its performance.
  We present an adaptive smoother which is used to reduce the computational cost in
  the regions with low residuals already. Compared to normal iterative solvers, our
  nonlinear FMG method provides faster convergence and better performance for both
  Newton's method and Projective Dynamics. Our experiment shows our method is efficient,
  accurate, stable against large time steps, and friendly with GPU parallelization.
  The performance of the method has a good scalability to the mesh resolution, and
  the method has good potential to be combined with multi-resolution collision handling
  for real-time simulation in the future.
summary: We explore nonlinearity, adaptive
  smoothing, and parallelization under a full multigrid (FMG) framework. The foundation
  of this research is a novel nonlinear FMG method for unstructured meshes.
tags:
- physical simulation
links:
url_video: https://drive.google.com/file/d/146ZnuGbPZzvqREQzYnIzLfXn4nSZGi13/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/WqWieqEEs_k?si=X2Yn2orbztUCjySr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=980298696&bvid=BV1n44y1P7wU&cid=563649326&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
