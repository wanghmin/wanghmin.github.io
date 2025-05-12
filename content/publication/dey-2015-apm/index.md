---
title: Automatic Posing of a Meshed Human Model Using Point Clouds
authors:
- Tamal K. Dey
- Bo Fu
- admin
- Lei Wang
date: '2015-02-01'
publishDate: '2024-03-03T02:42:26.878923Z'
publication_types:
- article-journal
publication: '*Computers & Graphics (Shape Modeling International), 16*'

abstract: We introduce a markerless approach to deform a quality human body template
  mesh from its original pose to a different pose specified by a point cloud. The
  point cloud may be noisy, incomplete, or even captured from a different person.
  In this approach, we first build coarse correspondences between the template mesh
  and the point cloud through a squeezed spectral embedding technique that exploits
  human body extremities. Based on these correspondences, we define the goal of non-rigid
  registration using an elastic energy functional and apply a discrete gradient flow
  to reduce the difference between a coarse control mesh and the point cloud. The
  deformed template mesh can then be obtained from the deformation of the control
  mesh using mean value coordinates afterwards. Our experiments show (see the supplementary
  video) that the approach is capable of equipping a mesh with the pose of a scanned
  point cloud data even if it is incomplete and noisy.
summary: 'We introduce a markerless approach to deform a quality human body template
  mesh from its original pose to a different pose specified by a point cloud. The
  point cloud may be noisy, incomplete, or even captured from a different person.'
tags:
- non-rigid registration
- deformation
- physically based modeling
links:
url_video: https://drive.google.com/file/d/1jVo9ByTC5xFEkEazIwPpM6dUeGvYd5Mc/view
url_slides: publication/dey-2015-apm/Dey-2015-APM.pptx
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/pMy22-HM-No?si=C-lrvsJXZcON8SHP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=595349737&bvid=BV1Qq4y1h7A1&cid=563601339&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
