---
title: A Chebyshev Semi-Iterative Approach for Accelerating Projective and Position-Based
  Dynamics
authors:
- Huamin Wang
date: '2015-11-01'
publishDate: '2024-03-03T02:42:26.916705Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia), 34*(6)'

abstract: In this paper, we study the use of the Chebyshev semi-iterative approach
  in projective and position-based dynamics. Although projective dynamics is fundamentally
  nonlinear, its convergence behavior is similar to that of an iterative method solving
  a linear system. Because of that, we can estimate the \"spectral radius\" and use
  it in the Chebyshev approach to accelerate the convergence by at least one order
  of magnitude, when the global step is handled by the direct solver, the Jacobi solver,
  or even the Gauss-Seidel solver. Our experiment shows that the combination of the
  Chebyshev approach and the direct solver runs fastest on CPU, while the combination
  of the Chebyshev approach and the Jacobi solver outperforms any other combination
  on GPU, as it is highly compatible with parallel computing. Our experiment further
  shows position-based dynamics can be accelerated by the Chebyshev approach as well,
  although the effect is less obvious for tetrahedral meshes. The whole approach is
  simple, fast, effective, GPU-friendly, and has a small memory cost.
summary: We study the use of the Chebyshev semi-iterative approach
  in projective and position-based dynamics. Our experiment shows the whole approach is
  simple, fast, effective, GPU-friendly, and has a small memory cost.
tags:
- Chebyshev semi-iterative method
- Jacobi method
- parallel computing
- position-based dynamics
- projective dynamics
links:
url_video: https://drive.google.com/file/d/1t1aqH57aIkIOULztcbytl70NzuS0AMDj/view
url_code: publication/wang-2015-csi/Wang-2015-CSI.zip
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/i-ySKIT5FVQ?si=W8Q8ZNbn_FgMGKOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=637816260&bvid=BV1sY4y1v7au&cid=563637274&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
