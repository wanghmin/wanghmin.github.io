---
title: Descent Methods for Elastic Body Simulation on the GPU
authors:
- admin
- Yin Yang
date: '2016-12-01'
publishDate: '2024-03-03T02:42:26.945756Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia), 35*(6)'

abstract: We show that many existing elastic body simulation approaches can be interpreted
  as descent methods, under a nonlinear optimization framework derived from implicit
  time integration. The key question is how to find an effective descent direction
  with a low computational cost. Based on this concept, we propose a new gradient
  descent method using Jacobi preconditioning and Chebyshev acceleration. The convergence
  rate of this method is comparable to that of L-BFGS or nonlinear conjugate gradient.
  But unlike other methods, it requires no dot product operation, making it suitable
  for GPU implementation. To further improve its convergence and performance, we develop
  a series of step length adjustment, initialization, and invertible model conversion
  techniques, all of which are compatible with GPU acceleration. Our experiment shows
  that the resulting simulator is simple, fast, scalable, memory-efficient, and robust
  against very large time steps and deformations. It can correctly simulate the deformation
  behaviors of many elastic materials, as long as their energy functions are second-order
  differentiable and their Hessian matrices can be quickly evaluated. For additional
  speedups, the method can also serve as a complement to other techniques, such as
  multi-grid.
summary: We show many elastic body simulation approaches can be interpreted
  as descent methods. Based on this concept, we propose a new gradient
  descent method using Jacobi preconditioning and Chebyshev acceleration.
tags:
- the Chebyshev method
- nonlinear optimization
- Jacobi preconditioning
- hyperelasticity
- GPU acceleration
links:
url_video: https://drive.google.com/file/d/1p9Q_yDC_gaS5IDCGNB9GOzQDFogomnmM/view
url_code: publication/wang-2016-dme/Wang-2016-DME.zip
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/qAF4EUeJTI4?si=3fF47hSjTTLLBoyq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=255255479&bvid=BV1tY411J7w9&cid=563649251&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
