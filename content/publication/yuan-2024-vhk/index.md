---
title: Volumetric Homogenization for Knitwear Simulation
authors:
- Chun Yuan
- Haoyang Shi
- Lei Lan
- Yuxing Qiu
- Cem Yuksel
- admin
- Chenfanfu Jiang
- Kui Wu
- Yin Yang
date: '2024-12-03'
publishDate: '2024-10-14T09:55:39.582190Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia)*'

abstract: This paper presents volumetric homogenization, a spatially varying homogenization
  scheme for knitwear simulation. We are motivated by the observation that macro-scale
  fabric dynamics is strongly correlated with its underlying knitting patterns. Therefore,
  homogenization towards a single material is less effective when the knitting is
  complex and non-repetitive. Our method tackles this challenge by homogenizing the
  yarn-level material locally at volumetric elements. Assigning a virtual volume of
  a knitting structure enables us to model bending and twisting effects via a simple
  volume-preserving penalty and thus effectively alleviates the material nonlinearity.
  We employ an adjoint Gauss-Newton formulation [Zehnder et al. 2021] to battle the
  dimensionality challenge of such per-element material optimization. This intuitive
  material model makes the forward simulation GPU-friendly. To this end, our pipeline
  also equips a novel domain-decomposed subspace solver crafted for GPU projective
  dynamics, which makes our simulator hundreds of times faster than the yarn-level
  simulator. Experiments validate the capability and effectiveness of volumetric homogenization.
  Our method produces realistic animations of knitwear matching the quality of full-scale
  yarn-level simulations. It is also orders of magnitude faster than existing homogenization
  techniques in both the training and simulation stages.
tags:
- yarn-level simulation
- homogenization
- physics-based simulation
- domain decomposition
summary: This paper presents volumetric homogenization, a spatially varying homogenization
  scheme for knitwear simulation.
featured: true
links:
- name: More Video
  url: Yuan-2024-VHK_supp.mp4
url_video: https://drive.google.com/file/d/1FK00-Wz4tWeMs_sTf_A2eUjucMgq868k/view?usp=sharing
---
<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/qgEFIVEPkIc?si=THx1QH8hbZUh_K12" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?isOutside=true&aid=113309541991697&bvid=BV1dQmnYyEcY&cid=26297434951&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
</p>
