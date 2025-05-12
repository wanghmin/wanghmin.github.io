---
title: Automatic Digital Garment Initialization from Sewing Patterns
authors:
- Chen Liu
- Weiwei Xu
- Yin Yang
- admin
date: '2024-07-28'
publishDate: '2024-10-14T09:55:39.566669Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH)*'

abstract: The rapid advancement of digital fashion and generative AI technology calls
  for an automated approach to transform digital sewing patterns into well-fitted
  garments on human avatars. When given a sewing pattern with its associated sewing
  relationships, the primary challenge is to establish an initial arrangement of sewing
  pieces that is free from folding and intersections. This setup enables a physics-based
  simulator to seamlessly stitch them into a digital garment, avoiding undesirable
  local minima. To achieve this, we harness AI classification, heuristics, and numerical
  optimization. This has led to the development of an innovative hybrid system that
  minimizes the need for user intervention in the initialization of garment pieces.
  The seeding process of our system involves the training of a classification network
  for selecting seed pieces, followed by solving an optimization problem to determine
  their positions and shapes. Subsequently, an iterative selection-arrangement procedure
  automates the selection of pattern pieces and employs a phased initialization approach
  to mitigate local minima associated with numerical optimization. Our experiments
  confirm the reliability, efficiency, and scalability of our system when handling
  intricate garments with multiple layers and numerous pieces. According to our findings,
  68 percent of garments can be initialized with zero user intervention, while the
  remaining garments can be easily corrected through user operations.
tags:
- physics-based cloth simulation
- numerical optimization
- digital fashion
- local minima
- sewing pattern
summary: We develop an innovative hybrid system for fast initialization of garment pieces with minimal user intervention, by harnessing AI classification, heuristics, and numerical optimization.
links:
- name: More Video
  url: Liu-2024-ADG_supp.mp4
tags:
- physics-based cloth simulation
- numerical optimization
- digital fashion
- local minima
- sewing pattern
url_video: https://drive.google.com/file/d/1Wd12MOPx5vOuInssPfniV1a1y_KlgZgG/view
url_dataset: https://www.kaggle.com/datasets/style3d/stylexda-multi-modal-benchmark-of-fashion
---
<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/v59XExb1fOU?si=vIVxCpQWdSmkVYfE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?isOutside=true&aid=112692090114031&bvid=BV1tp3WevEpb&cid=500001598414240&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
</p>
