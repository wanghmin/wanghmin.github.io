---
title: Bilateral Blue Noise Sampling
authors:
- Jiating Chen
- Xiaoyin Ge
- Li-Yi Wei
- Bin Wang
- Yusu Wang
- admin
- Yun Fei
- Kang-Lai Qian
- Jun-Hai Yong
- Wenping Wang
date: '2013-11-01'
publishDate: '2024-03-01T07:51:40.620667Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia), 32*(6)'

abstract: Blue noise sampling is an important component in many graphics applications,
  but existing techniques consider mainly the spatial positions of samples, making
  them less effective when handling problems with non-spatial features. Examples include
  biological distribution in which plant spacing is influenced by non-positional factors
  such as tree type and size, photon mapping in which photon flux and direction are
  not a direct function of the attached surface, and point cloud sampling in which
  the underlying surface is unknown a priori. These scenarios can benefit from blue
  noise sample distributions, but cannot be adequately handled by prior art. Inspired
  by bilateral filtering, we propose a bilateral blue noise sampling strategy. Our
  key idea is a general formulation to modulate the traditional sample distance measures,
  which are determined by sample position in spatial domain, with a similarity measure
  that considers arbitrary per sample attributes. This modulation leads to the notion
  of bilateral blue noise whose properties are influenced by not only the uniformity
  of the sample positions but also the similarity of the sample attributes. We describe
  how to incorporate our modulation into various sample analysis and synthesis methods,
  and demonstrate applications in object distribution, photon density estimation,
  and point cloud sub-sampling.
summary: 'Inspired by bilateral filtering, we propose a bilateral blue noise sampling strategy.
Our key idea is a general formulation to modulate the traditional sample distance measures,
with a similarity measure that considers arbitrary per sample attributes.'
tags:
- bilateral measure
- blue noise
- object distribution
- photon mapping
- point cloud
- stochastic sampling
links:
url_video: https://drive.google.com/file/d/17G2NkwbFhHBaVVWq8Oc485OBgwX6WNp7/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/hTBN_RB6JeY?si=MxKgqJ44lP26D7ar" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=640335433&bvid=BV1EY4y1W7aG&cid=563601335&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
