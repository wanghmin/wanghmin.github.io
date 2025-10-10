---
title: One-shot Embroidery Customization via Contrastive LoRA Modulation
authors:
- Jun Ma
- Qian He
- Gaofeng He
- Huang Chen
- Chen Liu
- Xiaogang Jin
- admin
date: '2025-12-02'
publishDate: '2025-10-10T08:37:01.301957Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia), 44*(6)'

abstract: 'Diffusion models have significantly advanced image manipulation techniques,
  and their ability to generate photorealistic images is beginning to transform retail
  workflows, particularly in presale visualization. Beyond artistic style transfer,
  the capability to perform fine-grained visual feature transfer is becoming increasingly
  important. Embroidery is a textile art form characterized by intricate interplay
  of diverse stitch patterns and material properties, which poses unique challenges
  for existing style transfer methods. To explore the customization for such fine-grained
  features, we propose a novel contrastive learning framework that disentangles fine-grained
  style and content features with a single reference image, building on the classic
  concept of image analogy. We first construct an image pair to define the target
  style, and then adopt a similarity metric based on the decoupled representations
  of pretrained diffusion models for style-content separation. Subsequently, we propose
  a two-stage contrastive LoRA modulation technique to capture fine-grained style
  features. In the first stage, we iteratively update the whole LoRA and the selected
  style blocks to initially separate style from content. In the second stage, we design
  a contrastive learning strategy to further decouple style and content through self-knowledge
  distillation. Finally, we build an inference pipeline to handle image or text inputs
  with only the style blocks. To evaluate our method on fine-grained style transfer,
  we build a benchmark for embroidery customization. Our approach surpasses prior
  methods on this task and further demonstrates strong generalization to three additional
  domains: artistic style transfer, sketch colorization, and appearance transfer.
  Our project is available at: https://style3d.github.io/embroidery_customization.'
tags:
- embroidery customization
- one-shot
- low-rank adaptation
- contrastive learning
links:
- name: Page
  url: https://style3d.github.io/embroidery_customization/
url_code: https://github.com/Style3D/embroidery_customization-impl
---
