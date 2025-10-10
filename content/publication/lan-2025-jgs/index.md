---
title: 'JGS2: Near Second-order Converging Jacobi/Gauss-Seidel for GPU Elastodynamics'
authors:
- Lei Lan
- Zixuan Lu
- Chun Yuan
- Weiwei Xu
- Hao Su
- Huamin Wang
- Chenfanfu Jiang
- Yin Yang
date: '2025-07-01'
publishDate: '2025-10-10T08:37:01.271116Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH)*'
doi: 10.1145/3731183
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
- name: URL
  url: https://doi.org/10.1145/3731183
---
