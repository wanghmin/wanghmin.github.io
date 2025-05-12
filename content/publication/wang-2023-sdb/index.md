---
title: Stable Discrete Bending by Analytic Eigensystem and Adaptive Orthotropic Geometric
  Stiffness
authors:
- Zhendong Wang
- Yin Yang
- admin
date: '2023-12-01'
publishDate: '2024-03-03T02:42:27.096003Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia), 42*(6)'

abstract: In this paper, we address two limitations of dihedral angle based discrete
  bending (DAB) models, i.e. the indefiniteness of their energy Hessian and their
  vulnerability to geometry degeneracies. To tackle the indefiniteness issue, we present
  novel analytic expressions for the eigensystem of a DAB energy Hessian. Our expressions
  reveal that DAB models typically have positive, negative, and zero eigenvalues,
  with four of each, respectively. By using these expressions, we can efficiently
  project an indefinite DAB energy Hessian as positive semi-definite analytically.
  To enhance the stability of DAB models at degenerate geometries, we propose rectifying
  their indefinite geometric stiffness matrix by using orthotropic geometric stiffness
  matrices with adaptive parameters calculated from our analytic eigensystem. Among
  the twelve motion modes of a dihedral element, our resulting Hessian for DAB models
  retains only the desirable bending modes, compared to the undesirable altitude-changing
  modes of the exact Hessian with original geometric stiffness, all modes of the Gauss-Newton
  approximation without geometric stiffness, and no modes of the projected Hessians
  with inappropriate geometric stiffness. Additionally, we suggest adjusting the compression
  stiffness according to the Kirchhoff-Love thin plate theory to avoid over-compression.
  Our method not only ensures the positive semidefiniteness but also avoids instability
  caused by large bending forces at degenerate geometries. To demonstrate the benefit
  of our approaches, we show comparisons against existing methods on the simulation
  of cloth and thin plates in challenging examples.
summary: In this paper, we address two limitations of dihedral angle based discrete
  bending (DAB) models, i.e. the indefiniteness of their energy Hessian and their
  vulnerability to geometry degeneracies.
tags:
- geometric stiffness
- eigensystem
- discrete bending
- dihedral angle
links:
url_video: https://drive.google.com/file/d/1KfusmPps_TDUhepNis2Zcj-KZQkwbp2c/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/R3662SYC4D4?si=nYq27zh7WAexgs8G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=321009762&bvid=BV1iw411i7uy&cid=1271234149&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
