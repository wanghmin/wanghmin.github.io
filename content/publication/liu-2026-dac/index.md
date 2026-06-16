---
title: Distributed Affine Body Dynamics with Adaptive Consensus
authors:
- Jiafeng Liu
- Wenhui Zhou
- Xinming Pei
- Yifan Peng
- admin
- Yin Yang
- Lei Lan
- Weiwei Xu
date: '2026-08-01'
publishDate: '2026-06-16T00:00:00Z'
publication_types:
- paper-conference
publication: '*ACM SIGGRAPH 2026 Conference Papers*'
abstract: Affine Body Dynamics (ABD) within the Incremental Potential Contact (IPC) framework provides accurate simulation of extremely stiff solids with near-rigid behavior and strict non-penetration guarantees. However, IPC's globally coupled barrier constraints make it difficult to scale across multiple GPUs and compute nodes. This work introduces a distributed ABD formulation based on adaptive consensus, allowing each compute node to solve a local subproblem in parallel while a global consensus step maintains consistency across shared boundary bodies. The method preserves IPC-level robustness and global consistency under distributed execution, and experiments demonstrate stable convergence, non-penetration, and efficient scaling on large scenes across multiple nodes.
summary: We propose a distributed Affine Body Dynamics method with adaptive consensus to scale robust IPC-based simulation across multiple GPUs and compute nodes.
tags:
- affine body dynamics
- adaptive consensus
- distributed simulation
---
