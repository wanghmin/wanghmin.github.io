---
title: Efficient Object Reconstruction with Differentiable Area Light Shading
authors:
- Yaoan Gao
- Jiamin Xu
- James Tompkin
- Qi Wang
- Zheng Dong
- Hujun Bao
- Yujun Shen
- admin
- Changqing Zou
- Weiwei Xu
date: '2025-12-01'
publishDate: '2025-10-10T08:37:01.294520Z'
publication_types:
- paper-conference
publication: '*SIGGRAPH Asia 2025 Conference Papers*'

abstract: 'In 3D object reconstruction from photographs, estimating material properties
  is challenging.We propose an inverse rendering method that uses active area lighting:
  as this provides a wider range of lighting angles per photo than point lighting,
  material reconstruction can be more accurate for the same number of photos. We compare
  area light shading with point lighting. With either mesh or 3D Gaussian splatting
  pipelines, area lighting can improve BRDF reconstruction and leads to +3 dB relighting
  PSNR over point lights, or need only 1/5 of the input photos for the same quality.
  We also compare area light shading with Monte Carlo ray tracing and with differential
  linearly transformed cosines (LTC) plus shadow visibility weighting. LTC can be
  faster, improving optimization times by 25%. In SOTA method-level comparisons, our
  approach improves material reconstruction, particularly for material roughness,
  leading to superior relighting quality.'
tags:
- inverse Rendering
- point light
- area light
- linearly transformed cosines
links:
url_video: https://drive.google.com/file/d/1TUhfjm9U1V_Rj2wqrhohE097Hewdah_g/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/QcwySh1qA4A?si=duIU-D8CzlPmFHPk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?isOutside=true&aid=115354416189099&bvid=BV1Mg4wzBEFr&cid=32989054378&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
