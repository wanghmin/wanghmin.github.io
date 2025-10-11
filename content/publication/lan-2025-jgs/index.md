---
title: 'JGS2: Near Second-order Converging Jacobi/Gauss-Seidel for GPU Elastodynamics'
authors:
- Lei Lan
- Zixuan Lu
- Chun Yuan
- Weiwei Xu
- Hao Su
- admin
- Chenfanfu Jiang
- Yin Yang
date: '2025-08-12'
publishDate: '2025-10-10T08:37:01.271116Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH), 44*(4)'

abstract: In parallel simulation, convergence and parallelism are often seen as inherently
  conflicting objectives. Improved parallelism typically entails lighter local computation
  and weaker coupling, which unavoidably slow the global convergence. This paper presents
  a novel GPU algorithm that achieves convergence rates comparable to fullspace Newton's
  method while maintaining good parallelizability just like the Jacobi method. Our
  approach is built on a key insight into the phenomenon of overshoot. Overshoot occurs
  when a local solver aggressively minimizes its local energy without accounting for
  the global context, resulting in a local update that undermines global convergence.
  To address this, we derive a theoretically second-order optimal solution to mitigate
  overshoot. Furthermore, we adapt this solution into a pre-computable form. Leveraging
  Cubature sampling, our runtime cost is only marginally higher than the Jacobi method,
  yet our algorithm converges nearly quadratically as Newton's method. We also introduce
  a novel full-coordinate formulation for more efficient pre-computation. Our method
  integrates seamlessly with the incremental potential contact method and achieves
  second-order convergence for both stiff and soft materials. Experimental results
  demonstrate that our approach delivers high-quality simulations and outperforms
  state-of-the-art GPU methods with 50× to 100× better convergence.
tags:
- GPU simulation
- second-order jacobi method
- newton's method
- numerical optimization
- parallel computation
links:
url_video: https://drive.google.com/file/d/19YTzkYbGTsBXUX3_dLlnZvpcXBo499JD/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/U7kX2zSqu5s?si=b3ODOnZRRH26bObm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?isOutside=true&aid=115349282491022&bvid=BV1Ek4Jz6Ev7&cid=32967491898&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
