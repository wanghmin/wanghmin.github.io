---
title: Parallel Multigrid for Nonlinear Cloth Simulation
authors:
- Zhendong Wang
- Longhua Wu
- Marco Fratarcangeli
- Min Tang
- Huamin Wang
date: '2018-10-01'
publishDate: '2024-03-03T02:42:26.975107Z'
publication_types:
- article-journal
publication: '*Computer Graphics Forum (Pacific Graphics, best paper award)*'
doi: https://doi.org/10.1111/cgf.13554
abstract: Abstract Accurate high-resolution simulation of cloth is a highly desired
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
tags:
- CCS Concepts
- •Computing methodologies → Physical simulation
links:
- name: URL
  url: https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13554
---