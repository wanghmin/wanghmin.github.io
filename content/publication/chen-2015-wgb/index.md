---
title: 'Wetbrush: GPU-Based 3D Painting Simulation at the Bristle Level'
authors:
- Zhili Chen
- Byungmoon Kim
- Daichi Ito
- Huamin Wang
date: '2015-11-01'
publishDate: '2024-03-03T02:42:26.893868Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia)*'
doi: 10.1145/2816795.2818066
abstract: 'We present a real-time painting system that simulates the interactions
  among brush, paint, and canvas at the bristle level. The key challenge is how to
  model and simulate sub-pixel paint details, given the limited computational resource
  in each time step. To achieve this goal, we propose to define paint liquid in a
  hybrid fashion: the liquid close to the brush is modeled by particles, and the liquid
  away from the brush is modeled by a density field. Based on this representation,
  we develop a variety of techniques to ensure the performance and robustness of our
  simulator under large time steps, including brush and particle simulations in non-inertial
  frames, a fixed-point method for accelerating Jacobi iterations, and a new Eulerian-Lagrangian
  approach for simulating detailed liquid effects. The resulting system can realistically
  simulate not only the motions of brush bristles and paint liquid, but also the liquid
  transfer processes among different representations. We implement the whole system
  on GPU by CUDA. Our experiment shows that artists can use the system to draw realistic
  and vivid digital paintings, by applying the painting techniques that they are familiar
  with but not offered by many existing systems.'
tags:
- non-inertial frame
- fluid simulation
- fluid coupling
- eulerian-lagrangian
- brush and hair
- GPU computing
- FLIP/PIC
links:
- name: URL
  url: https://doi.org/10.1145/2816795.2818066
---