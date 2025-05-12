---
title: GPU-Based Simulation of Cloth Wrinkles at Submillimeter Levels
authors:
- admin
date: '2021-07-01'
publishDate: '2024-03-03T02:42:27.042912Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH), 40*(4)'

abstract: In this paper, we study physics-based cloth simulation in a very high resolution
  setting, presumably at submillimeter levels with millions of vertices, to meet perceptual
  precision of our human eyes. State-of-the-art simulation techniques, mostly developed
  for unstructured triangular meshes, can hardly meet this demand due to their large
  computational costs and memory footprints. We argue that in a very high resolution,
  it is more plausible to use regular meshes with an underlying grid structure, which
  can be highly compatible with GPU acceleration like high-resolution images. Based
  on this idea, we formulate and solve the nonlinear optimization problem for simulating
  high-resolution wrinkles, by a fast block-based descent method with reduced memory
  accesses. We also investigate the development of the collision handling component
  in our system, whose performance benefits greatly from the grid structure. Finally,
  we explore various issues related to the applications of our system, including initialization
  for fast convergence and temporal coherence, gathering effects, inflation and stuffing
  models, and mesh simplification. We can treat our system as a quasistatic wrinkle
  synthesis tool, run it as a standalone dynamic simulator, or integrate it into a
  multi-resolution solver as an additional component. The experiment demonstrates
  the capability, efficiency and flexibility of our system in producing a variety
  of high-resolution wrinkles effects.
summary: 'In this paper, we study physics-based cloth simulation in a very high resolution
  setting, presumably at submillimeter levels with millions of vertices, to meet perceptual
  precision of our human eyes.'
tags:
- GPU acceleration
- cloth simulation
- collision handling
- parallel computing
- wrinkle synthesis
links:
url_video: https://drive.google.com/file/d/1iXd3FmlS__CVnOMAAFsU9VHel7FSIV6z/view
url_code: publication/wang-2021-gbs/Wang-2021-GBS.zip
url_source: publication/wang-2021-gbs/Wang-2021-GBS-supp.zip
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/g1DBScutcOQ?si=TGlT2T6zr4xLbGWP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=255368167&bvid=BV18Y411773w&cid=563649259&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
