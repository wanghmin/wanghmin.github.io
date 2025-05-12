---
title: Learning-Based Bending Stiffness Parameter Estimation by a Drape Tester
authors:
- Xudong Feng
- Wenchao Huang
- Weiwei Xu
- admin
date: '2022-11-01'
publishDate: '2024-03-03T02:42:27.058210Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia), 41*(6)'

abstract: 'Real-world fabrics often possess complicated nonlinear, anisotropic bending
  stiffness properties. Measuring the physical parameters of such properties for physics-based
  simulation is difficult yet unnecessary, due to the persistent existence of numerical
  errors in simulation technology. In this work, we propose to adopt a simulation-in-the-loop
  strategy: instead of measuring the physical parameters, we estimate the simulation
  parameters to minimize the discrepancy between reality and simulation. This strategy
  offers good flexibility in test setups, but the associated optimization problem
  is computationally expensive to solve by numerical methods. Our solution is to train
  a regression-based neural network for inferring bending stiffness parameters, directly
  from drape features captured in the real world. Specifically, we choose the Cusick
  drape test method and treat multiple-view depth images as the feature vector. To
  effectively and efficiently train our network, we develop a highly expressive and
  physically validated bending stiffness model, and we use the traditional cantilever
  test to collect the parameters of this model for 618 real-world fabrics. Given the
  whole parameter data set, we then construct a parameter subspace, generate new samples
  within the sub-space, and finally simulate and augment synthetic data for training
  purposes. The experiment shows that our trained system can replace cantilever tests
  for quick, reliable and effective estimation of simulation-ready parameters. Thanks
  to the use of the system, our simulator can now faithfully simulate bending effects
  comparable to those in the real world.'
summary: 'In this work, we propose to adopt a simulation-in-the-loop strategy for
  fabric parameter estimation and we train a regression-based neural network for
  inferring bending stiffness parameters from Cusick drap tests.'
tags:
- parameter estimation
- material property acquisition
- deep neural networks
- cloth simulation
- bending stiffness
links:
url_video: https://drive.google.com/file/d/14NIYA-CXXxU7EdiQnk70hSJN5lsqRW13/view
url_code: https://github.com/DrapeTester/ClothDrapeTester
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/4PfgBnVCeNY?si=3yeD4T3uPQ001ZxL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=858160039&bvid=BV1eV4y1M7Yr&cid=837387296&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
