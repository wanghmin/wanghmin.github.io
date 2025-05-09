---
title: Animating Bubble Interactions in a Liquid Foam
authors:
- Oleksiy Busaryev
- Tamal K. Dey
- admin
- Zhong Ren
date: '2012-07-01'
publishDate: '2024-03-01T07:51:40.599523Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH), 31*(4)'

abstract: Bubbles and foams are important features of liquid surface phenomena, but
  they are difficult to animate due to their thin films and complex interactions in
  the real world. In particular, small bubbles (having diameter <1cm) in a dense foam
  are highly affected by surface tension, so their shapes are much less deformable
  compared with larger bubbles. Under this small bubble assumption, we propose a more
  accurate and efficient particle-based algorithm to simulate bubble dynamics and
  interactions. The key component of this algorithm is an approximation of foam geometry,
  by treating bubble particles as the sites of a weighted Voronoi diagram. The connectivity
  information provided by the Voronoi diagram allows us to accurately model various
  interaction effects among bubbles. Using Voronoi cells and weights, we can also
  explicitly address the volume loss issue in foam simulation, which is a common problem
  in previous approaches. Under this framework, we present a set of bubble interaction
  forces to handle miscellaneous foam behaviors, including foam structure under Plateau's
  laws, clusters formed by liquid surface bubbles, bubble-liquid and bubble-solid
  coupling, bursting and coalescing. Our experiment shows that this method can be
  straightforwardly incorporated into existing liquid simulators, and it can efficiently
  generate realistic foam animations, some of which have never been produced in graphics
  before.
summary: Bubbles and foams are important features of liquid surface phenomena, but
  they are difficult to animate. We propose a more accurate and efficient
  particle-based algorithm to simulate bubble dynamics and interactions.
tags:
- weighted Voronoi diagram
- surface tension
- natural phenomena
- liquid
- foam
- bubble interaction
links:
url_video: https://drive.google.com/file/d/13owYIdfDrSuqF3Ua5B5dX66rKd3_iKni/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/GPbFp50ZGUE?si=70WF-v7vmnFpf-ir" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=552815045&bvid=BV1Qi4y1Q7Xr&cid=563594875&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
