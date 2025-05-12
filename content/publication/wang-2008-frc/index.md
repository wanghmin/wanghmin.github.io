---
title: Factoring Repeated Content within and among Images
authors:
- admin
- Yonatan Wexler
- Eyal Ofek
- Hugues Hoppe
date: '2008-08-01'
publishDate: '2024-02-29T05:26:53.848532Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH), 27*(3)'

abstract: We reduce transmission bandwidth and memory space for images by factoring
  their repeated content. A transform map and a condensed epitome are created such
  that all image blocks can be reconstructed from transformed epitome patches. The
  transforms may include affine deformation and color scaling to account for perspective
  and tonal variations across the image. The factored representation allows efficient
  random-access through a simple indirection, and can therefore be used for real-time
  texture mapping without expansion in memory. Our scheme is orthogonal to traditional
  image compression, in the sense that the epitome is amenable to further compression
  such as DXT. Moreover it allows a new mode of progressivity, whereby generic features
  appear before unique detail. Factoring is also effective across a collection of
  images, particularly in the context of image-based rendering. Eliminating redundant
  content lets us include textures that are several times as large in the same memory
  space.
summary: We reduce transmission bandwidth and memory space for images by factoring
  their repeated content. Eliminating redundant content lets us include textures
  that are several times as large in the same memory space.
tags:
- image compression
- image epitomes
- progressive images
featured: false
links:
url_slides: http://research.microsoft.com/~hoppe/factorimage.pptx
---
