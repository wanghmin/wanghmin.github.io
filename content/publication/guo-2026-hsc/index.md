---
featured: true
title: Heterogeneous Subspace Corrections for GPU Deformable Multibody Dynamics
authors:
- Dewen Guo
- Zhendong Wang
- Minchen Li
- Sheng Li
- Guoping Wang
- admin
- Chenfanfu Jiang
- Yin Yang
date: '2026-08-01'
publishDate: '2026-06-16T00:00:00Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH), 45*(4)'
tags:
- deformable multibody dynamics
- GPU simulation
- subspace corrections
doi: "10.1145/3811275"
summary: "We develop a GPU solver for multibody systems combining soft and stiff materials. Heterogeneous subspace corrections exploit low-rank coupling to accelerate deformable dynamics with challenging contacts."
abstract: "Simulating heterogeneous multibody systems with both deformable and stiff components remains a challenge for GPU solvers. While Newton-Krylov methods are popular for their matrix-free nature and good GPU compatibility, they often suffer from severe ill-conditioning and slow convergence when handling stiff contacts and material disparities in deformable multibody systems. In this paper, we present Heterogeneous Subspace Corrections (HSC), a novel Newton-CG variant to efficiently simulate such complex systems. HSC decouples the system into two Krylov iterations: a Newton-CG procedure for deformable bodies and a Neumann-based iteration for the affine subsystem. We introduce a GPU-based Adaptive Cross Approximation (ACA) algorithm to exploit the low-rank nature of the coupling matrices, which manages to reduce the overhead of sparse matrix-vector multiplications substantially on the GPU. For the affine subsystem, we propose a dedicated data structure for fast assembling contact Hessians in parallel. A variety of experimental results demonstrate that our framework consistently outperforms existing GPU simulators, achieving convergence rates comparable to direct solvers even in scenes with high-resolution models and extensive stiff contacts."
---
