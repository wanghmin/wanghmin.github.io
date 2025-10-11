---
title: 'FashionR2R: texture-preserving rendered-to-real image translation with diffusion
  models'
authors:
- Rui Hu
- Qian He
- Gaofeng He
- Jiedong Zhuang
- Huang Chen
- Huafeng Liu
- Huamin Wang
date: '2024-01-01'
publishDate: '2025-10-11T03:17:57.753521Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 38th International Conference on Neural Information
  Processing Systems*'
abstract: "Modeling and producing lifelike clothed human images has attracted researchers'
  attention from different areas for decades, with the complexity from highly articulated
  and structured content. Rendering algorithms decompose and simulate the imaging
  process of a camera, while are limited by the accuracy of modeled variables and
  the efficiency of computation. Generative models can produce impressively vivid
  human images, however still lacking in controllability and editability. This paper
  studies photorealism enhancement of rendered images, leveraging generative power
  from diffusion models on the controlled basis of rendering. We introduce a novel
  framework to translate rendered images into their realistic counterparts, which
  consists of two stages: Domain Knowledge Injection (DKI) and Realistic Image Generation
  (RIG). In DKI, we adopt positive (real) domain finetuning and negative (rendered)
  domain embedding to inject knowledge into a pretrained Text-to-image (T2I) diffusion
  model. In RIG, we generate the realistic image corresponding to the input rendered
  image, with a Texture-preserving Attention Control (TAC) to preserve fine-grained
  clothing textures, exploiting the decoupled features encoded in the UNet structure.
  Additionally, we introduce SynFashion dataset, featuring high-quality digital clothing
  images with diverse textures. Extensive experimental results demonstrate the superiority
  and effectiveness of our method in rendered-to-real image translation."
---
