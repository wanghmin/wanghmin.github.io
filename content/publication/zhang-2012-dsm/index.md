---
title: A Deformable Surface Model for Real-Time Water Drop Animation
authors:
- Yizhong Zhang
- admin
- Shuai Wang
- Yiying Tong
- Kun Zhou
date: '2012-08-01'
publishDate: '2024-03-01T07:51:40.577512Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Visualization and Computer Graphics, 18*(8)'

abstract: A water drop behaves differently from a large water body because of its
  strong viscosity and surface tension under the small scale. Surface tension causes
  the motion of a water drop to be largely determined by its boundary surface. Meanwhile,
  viscosity makes the interior of a water drop less relevant to its motion, as the
  smooth velocity field can be well approximated by an interpolation of the velocity
  on the boundary. Consequently, we propose a fast deformable surface model to realistically
  animate water drops and their flowing behaviors on solid surfaces. Our system efficiently
  simulates water drop motions in a Lagrangian fashion, by reducing 3D fluid dynamics
  over the whole liquid volume to a deformable surface model. In each time step, the
  model uses an implicit mean curvature flow operator to produce surface tension effects,
  a contact angle operator to change droplet shapes on solid surfaces, and a set of
  mesh connectivity updates to handle topological changes and improve mesh quality
  over time. Our numerical experiments demonstrate a variety of physically plausible
  water drop phenomena at a real-time rate, including capillary waves when water drops
  collide, pinch-off of water jets, and droplets flowing over solid materials. The
  whole system performs orders-of-magnitude faster than existing simulation approaches
  that generate comparable water drop effects.
summary: We propose a fast deformable surface model to realistically
  animate water drops and their flows on solid surfaces. Our system
  simulates drop motions in a Lagrangian fashion, by reducing 3D fluid dynamics
  to a deformable surface model. 
tags:
- solids
- surface tension
- viscosity
- force
- deformable models
- surface waves
- numerical models
- deformable surface model
- surface tension
- mean curvature flow
- water drop simulation
---
