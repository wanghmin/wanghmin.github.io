---
title: Fast GPU-Based Two-Way Continuous Collision Handling
authors:
- Tianyu Wang
- Jiong Chen
- Dongping Li
- Xiaowei Liu
- admin
- Kun Zhou
date: '2023-07-01'
publishDate: '2024-03-03T02:42:27.066106Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH), 42*(5)'

abstract: Step-and-project is a popular method to simulate non-penetrating deformable
  bodies in physically based animation. The strategy is to first integrate the system
  in time without considering contacts and then resolve potential intersections, striking
  a good balance between plausibility and efficiency. However, existing methods can
  be defective and unsafe when using large time steps, taking risks of failure or
  demanding repetitive collision testing and resolving that severely degrade performance.
  In this article, we propose a novel two-way method for fast and reliable continuous
  collision handling. Our method launches an optimization from both ends of the intermediate
  time-integrated state and the previous intersection-free state. It progressively
  generates a piecewise linear path and eventually obtains a feasible solution for
  the next time step. The algorithm efficiently alternates between a forward step
  and a backward step until the result is conditionally converged. Thanks to a set
  of unified volume-based contact constraints, our method offers flexible and reliable
  handling of various codimensional deformable bodies, including volumetric bodies,
  cloth, hair, and sand. Experimental results demonstrate the safety, robustness,
  physical fidelity, and numerical efficiency of our method, making it particularly
  suitable for scenarios involving large deformations or large time steps.
summary: We propose a novel two-way method for fast and reliable continuous
  collision handling. Our method launches an optimization from both ends of the intermediate
  time-integrated state and the previous intersection-free state.
tags:
- nonlinear optimization
- GPU computation
- deformable body simulation
- collision handling
links:
url_video: https://drive.google.com/file/d/1OHeNDsYlgutLgmr82b8d63hdh8BnqwRE/view
url_code: https://github.com/WTYatzoo/
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/6T52DU2iFu0?si=ehT7BX10SWjWsJyZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=229760909&bvid=BV14h411T7xG&cid=1165331205&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
