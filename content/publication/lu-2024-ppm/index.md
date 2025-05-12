---
title: Projective Peridynamic Modeling of Hyperelastic Membranes With Contact
authors:
- Zixuan Lu
- Xiaowei He
- Yuzhong Guo
- Xuehui Liu
- admin
date: '2024-08-01'
publishDate: '2024-11-13T06:03:43.097225Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Visualization and Computer Graphics, 30*(8)'

abstract: Real-time simulation of hyperelastic membranes like cloth still faces a
  lot of challenges, such as hyperplasticity modeling and contact handling. In this
  study, we propose projective peridynamics that uses a local-global strategy to enable
  fast and robust simulation of hyperelastic membranes with contact. In the global
  step, we propose a semi-implicit strategy to linearize the governing equation for
  hyperelastic materials that are modeled with peridynamics. By decomposing the first
  Piola-Kirchhoff stress tensor into a positive and a negative part, successive substitutions
  can be taken to solve the nonlinear problems. Convergence is guaranteed by further
  addressing the overshooting problem. Since our global step solve requires no energy
  summation and dot product operations over the entire problem, it fits into GPU implementation
  perfectly. In the local step, we further present a GPU-friendly gradient descent
  method to prevent interpenetration by solving an optimization problem independently.
  Putting the global and local solves together, experiments show that our method is
  robust and efficient in simulating complex models of membranes involving hyperelastic
  materials and contact.
summary: In this paper, we propose projective peridynamics that uses a local-global strategy to enable
  fast and robust simulation of hyperelastic membranes with contact.
tags:
- mathematical models
- convergence
- computational modeling
- real-time systems
- graphics processing units
- deformation
- software
- contact handling
- hyperelastic membranes
- projective peridynamics
- semi -implicit successive substitution method (SISSM)
url_code: https://github.com/peridyno/peridyno/tree/master/src/Dynamics/Cuda/Peridynamics

---
