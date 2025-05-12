---
title: A Dynamic Duo of Finite Elements and Material Points
authors:
- Xuan Li
- Minchen Li
- Xuchen Han
- admin
- Yin Yang
- Chenfanfu Jiang
date: '2024-07-28'
publishDate: '2024-10-14T09:55:39.558913Z'
publication_types:
- paper-conference
publication: '*ACM SIGGRAPH 2024 Conference Papers*'

abstract: 'This paper presents a novel method to couple Finite Element Methods (FEM),
  typically employed for modeling Lagrangian solids such as flesh, cloth, hair, and
  rigid bodies, with Material Point Methods (MPM), which are well-suited for simulating
  materials undergoing substantial deformation and topology change, including Newtonian/non-Newtonian
  fluid, granular materials, and fracturing materials. The challenge of coupling these
  diverse methods arises from their contrasting computational needs: implicit FEM
  integration is often favored to enjoy stability and large timesteps, while explicit
  MPM integration benefits from its allowance for efficient GPU optimization and flexibility
  of applying different plasticity models, which only allows for moderate timesteps.
  To bridge this gap, a mixed implicit-explicit time integration (IMEX) approach is
  proposed, utilizing principles from time splitting for partial differential equations
  and optimization-based time integrators. This method adopts incremental potential
  contact (IPC) to define a variational frictional contact model between the two materials,
  serving as the primary coupling mechanism. Our method enables implicit FEM and explicit
  MPM to coexist with significantly different timestep sizes while preserving two-way
  coupling. Experimental results demonstrate the potential of our method as a strong
  foundation for future exploration and enhancement in the field of multi-material
  simulation.'
tags:
- asynchronous time integration
- finite element method
- frictional contact
- material point method
- optimization time integration
- time splitting
summary: We present a novel method to couple Finite Element Methods (FEM),
  typically employed for modeling flesh, cloth, hair, and rigid bodies, with Material Point Methods (MPM), which are well-suited for simulating
  Newtonian/non-Newtonian fluid, granular materials, and fracturing materials.
---
<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/qSDfoOZwFpo?si=dTLF9skuZqFo5163" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
