---
title: Material Space Texturing
authors:
- Nicolas Ray
- Bruno Lévy
- admin
- Greg Turk
- Bruno Vallet
date: '2009-09-01'
publishDate: '2024-03-01T04:06:04.825547Z'
publication_types:
- article-journal
publication: '*Computer Graphics Forum, 28*(6)'

abstract: Many objects have patterns that vary in appearance at different surface
  locations. We say that these are differences in materials, and we present a material-space
  approach for interactively designing such textures. At the heart of our approach
  is a new method to pre-calculate and use a 3D texture tile that is periodic in the
  spatial dimensions (s, t) and that also has a material axis along which the materials
  change smoothly. Given two textures and their feature masks, our algorithm produces
  such a tile in two steps. The first step resolves the features morphing by a level
  set advection approach, improved to ensure convergence. The second step performs
  the texture synthesis at each slice in material-space, constrained by the morphed
  feature masks. With such tiles, our system lets a user interactively place and edit
  textures on a surface, and in particular, allows the user to specify which material
  appears at given positions on the object. Additional operations include changing
  the scale and orientation of the texture. We support these operations by using a
  global surface parameterization that is closely related to quad re-meshing. Re-parameterization
  is performed on-the-fly whenever the user's constraints are modified.
summary: Many objects have patterns that vary in appearance at different surface
  locations. We say that these are differences in materials, and we present a material-space
  approach for interactively designing such textures.
tags:
- texture mapping
- texture synthesis
- varying texture
featured: false
---
