---
title: 'FashionR2R: Texture-Preserving Rendered-to-Real Image Translation with Diffusion
  Models'
authors:
- Rui Hu
- Qian He
- Jiedong Zhuang
- Huang Chen
- Huafeng Liu
- admin
date: '2024-12-10'
publishDate: '2024-10-22T08:31:09.743820Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems 38: Annual Conference
  on Neural Information Processing Systems (NeurIPS)*'
abstract: 'Modeling and producing lifelike clothed human images has attracted researchers’
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
  and effectiveness of our method in rendered-to-real image translation.'
summary: We introduce a novel diffusion-based framework that effectively translates rendered
  images into realistic counterparts, ensuring the preservation of texture details.
links:
- name: Page
  url: https://rickhh.github.io/FashionR2R/ 
---
