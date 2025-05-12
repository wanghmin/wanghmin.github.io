---
title: Interactive Two-Way Shape Design of Elastic Bodies
authors:
- Rajaditya Mukherjee
- Longhua Wu
- admin
date: '2018-07-01'
publishDate: '2024-03-03T02:42:26.967370Z'
publication_types:
- article-journal
publication: '*Proc. ACM Comput. Graph. Interact. Tech. (I3D), 1*(1)'

abstract: We present a novel system for interactive elastic shape design in both forward
  and inverse fashions. Using this system, the user can choose to edit the rest shape
  or the quasistatic shape of an elastic solid, and obtain the other shape that matches
  under the quasistatic equilibrium condition at the same time. The development of
  this system is based on the discovery that inverse quasistatic simulation can be
  immediately solved by Newton's method with a direct solver. To implement our simulator,
  we propose a Jacobian matrix evaluation scheme for the inverse elastic problem and
  we present step length and matrix evaluation techniques that improve the simulation
  performance. While our simulator is efficient, it is still not fast enough for the
  system to generate the result in real time. Our solution is a shape initialization
  method using the recent projective dynamics technique. Shape initialization not
  only works as a fast preview function during the user editing process, but also
  speeds up the convergence of quasistatic or inverse quasistatic simulation afterwards.
  The use of a heterogeneous algorithm structure allows the system to further reduce
  its preview cost, by utilizing the power of both the CPU and the GPU. Our experiment
  demonstrates that the whole system is fast, robust, and convenient for the designer
  to use in both forward and inverse elastic shape design. It can handle a variety
  of nonlinear elastic material models, and its runtime performance has space for
  more improvement.
summary: We present a system for interactive elastic shape design in both forward
  and inverse fashions. Using it, a user can edit the rest shape or the quasistatic
  shape of an elastic solid, and obtain the other shape at the same time. 
tags:
- quasistatic simulation
- Newton's method
- inverse elastic problem
- hyperelasticity
- heterogeneous structure
links:
url_video: https://drive.google.com/file/d/1xS_j8ay82VHpJRcGPxAMWkjlFmbYMfQv/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/oBMdngBdCMg?si=AA5633uPiyADkGqa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=382788158&bvid=BV1zZ4y1m7kX&cid=563614287&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
