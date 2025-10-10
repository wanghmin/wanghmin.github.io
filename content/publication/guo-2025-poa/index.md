---
title: Progressive Outfit Assembly and Instantaneous Pose Transfer
authors:
- Dewen Guo
- Zhendong Wang
- Zegao Liu
- Sheng Li
- Guoping Wang
- Yin Yang
- admin
date: '2025-12-01'
publishDate: '2025-10-10T08:37:01.286987Z'
publication_types:
- paper-conference
publication: '*SIGGRAPH Asia 2025 Conference Papers*'

abstract: With the rise of digital fashion, reusing high-quality garment assets to
  assemble new outfits has become increasingly important for improving design efficiency
  and reducing production costs. However, combining multiple garments often introduces
  complex inter-garment intersections that are difficult to resolve. In this paper,
  we propose a novel framework that introduces a midsurface representation to simplify
  multilayered garments for intersection-free outfit assembly. Each garment is approximated
  by a watertight tetrahedral enclosure, enabling efficient resolution of inter-garment
  collisions on the midsurface level. To assemble an outfit, our method progressively
  untangles pairs of single-layer midsurfaces and incrementally constructs a merged
  midsurface. To recover the intersection-free full geometry from these deformed midsurfaces
  and enable instantaneous transfer across different poses, we uses embedded anchors
  to drive inversion-free deformation of enclosing tetrahedral cages. Through various
  examples, we demonstrate that our method provides a scalable and automated solution
  for virtual outfit coordination, enabling the direct reuse of garment assets in
  high-fidelity, collision-free digital fashion workflows.
tags:
- cloth simulation
- untangling
- embedded deformation
links:
url_video: https://drive.google.com/file/d/1srTvr1XJFmsCb-wEvE3iLa652a5u-ZBs/view
url_code: https://github.com/Style3D/OutfitAssembly
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/OpC2jaLPUgU?si=dWQSYLVBpKP2KLma" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?isOutside=true&aid=115349433421741&bvid=BV1Vg4JzaEZ4&cid=32968345412&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
</p>
