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
- Huamin Wang
- Changqing Zou
- Weiwei Xu
date: '2025-12-01'
publishDate: '2025-10-10T08:37:01.294520Z'
publication_types:
- paper-conference
publication: '*SIGGRAPH Asia 2025 Conference Papers*'
doi: 10.1145/3757377.3763865
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
- name: URL
  url: https://doi.org/10.1145/3757377.3763865
---
