---
title: Physics-Based Quadratic Deformation Using Elastic Weighting
authors:
- Ran Luo
- Weiwei Xu
- Huamin Wang
- Kun Zhou
- Yin Yang
date: '2018-12-01'
publishDate: '2024-03-03T02:42:26.982745Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Visualization and Computer Graphics, 24*(12)'

abstract: This paper presents a spatial reduction framework for simulating nonlinear deformable objects interactively. This reduced model is built using a small number of overlapping quadratic domains as we notice that incorporating high-order degrees of freedom (DOFs) is important for the simulation quality. Departing from existing multi-domain methods in graphics, our method interprets deformed shapes as blended quadratic transformations from nearby domains. Doing so avoids expensive safeguards against the domain coupling and improves the numerical robustness under large deformations. We present an algorithm that efficiently computes weight functions for reduced DOFs in a physics-aware manner. Inspired by the well-known multi-weight enveloping technique, our framework also allows subspace tweaking based on a few representative deformation poses. Such elastic weighting mechanism significantly extends the expressivity of the reduced model with light-weight computational efforts. Our simulator is versatile and can be well interfaced with many existing techniques. It also supports local DOF adaption to incorporate novel deformations (i.e., induced by the collision). The proposed algorithm complements state-of-the-art model reduction and domain decomposition methods by seeking for good trade-offs among animation quality, numerical robustness, pre-computation complexity and simulation efficiency from an alternative perspective.
summary: This paper presents a spatial reduction framework for simulating nonlinear deformable objects interactively.
  This reduced model is built using a small number of overlapping quadratic domains.
tags:
- strain
- deformable models
- shape
- computational modeling
- numerical models
- couplings
- adaptation models
- quadratic deformation
- FEM
- model reduction
- domain decomposition
- weight function
---
