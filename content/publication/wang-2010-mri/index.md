---
title: Multi-Resolution Isotropic Strain Limiting
authors:
- admin
- James O'Brien
- Ravi Ramamoorthi
date: '2010-12-01'
publishDate: '2024-03-01T07:51:40.562595Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia), 29*(6)'

abstract: In this paper we describe a fast strain-limiting method that allows stiff,
  incompliant materials to be simulated efficiently. Unlike prior approaches, which
  act on springs or individual strain components, this method acts on the strain tensors
  in a coordinate-invariant fashion allowing isotropic behavior. Our method applies
  to both two-and three-dimensional strains, and only requires computing the singular
  value decomposition of the deformation gradient, either a small 2x2 or 3x3 matrix,
  for each element. We demonstrate its use with triangular and tetrahedral linear-basis
  elements. For triangulated surfaces in three-dimensional space, we also describe
  a complementary edge-angle-limiting method to limit out-of-plane bending. All of
  the limits are enforced through an iterative, non-linear, Gauss-Seidel-like constraint
  procedure. To accelerate convergence, we propose a novel multi-resolution algorithm
  that enforces fitted limits at each level of a non-conforming hierarchy. Compared
  with other constraint-based techniques, our isotropic multi-resolution strain-limiting
  method is straightforward to implement, efficient to use, and applicable to a wide
  range of shell and solid materials.
summary: In this paper we describe a fast strain-limiting method that allows stiff,
  incompliant materials to be simulated efficiently. This method acts on the strain tensors
  in a coordinate-invariant fashion allowing isotropic behavior.
tags:
- strain limiting
- multi-resolution
- finite element method
links:
url_video: 'https://drive.google.com/file/d/1GfL6Lz4yYlYcBAkMyqw7hbzB_U8Rpp20/view'
---
<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/iZNGXwdGfFc?si=7xOyteQO3EpLPSw7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=212781905&bvid=BV1na41147Un&cid=563637271&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
