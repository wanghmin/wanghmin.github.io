---
title: 'GarmageNet: A Multimodal Generative Framework for Sewing Pattern Design and
  Generic Garment Modeling'
authors:
- Siran Li
- Ruiyang Liu
- Chen Liu
- Zhendong Wang
- Gaofeng He
- Yong-Lu Li
- Xiaogang Jin
- admin
date: '2025-12-01'
publishDate: '2025-10-10T08:37:01.309982Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia), 44*(6)'

abstract: Realistic digital garment modeling remains a labor-intensive task due to
  the intricate process of translating 2D sewing patterns into high-fidelity, simulation-ready
  3D garments. We introduce GarmageNet, a unified generative framework that automates
  the creation of 2D sewing patterns, the construction of sewing relationships, and
  the synthesis of 3D garment initializations compatible with physics-based simulation.
  Central to our approach is Garmage, a novel garment representation that encodes
  each panel as a structured geometry image, effectively bridging the semantic and
  geometric gap between 2D structural patterns and 3D garment geometries. Followed
  by GarmageNet, a latent diffusion transformer to synthesize panel-wise geometry
  images and GarmageJigsaw, a neural module for predicting point-to-point sewing connections
  along panel contours. To support training and evaluation, we build GarmageSet, a
  large-scale dataset comprising 14,801 professionally designed garments with detailed
  structural and style annotations. Our method demonstrates versatility and efficacy
  across multiple application scenarios, including scalable garment generation from
  multi-modal design concepts (text prompts, sketches, photographs), automatic modeling
  from raw flat sewing patterns, pattern recovery from unstructured point clouds,
  and progressive garment editing using conventional instructions, laying the foundation
  for fully automated, production-ready pipelines in digital fashion. Refer to our
  project page for open-sourced code and dataset.
tags:
- garment modeling
- garment dataset
- diffusion Generation
links:
- name: Page
  url: https://style3d.github.io/garmagenet/
url_code: https://github.com/Style3D/garmagenet-impl
url_dataset: https://huggingface.co/datasets/Style3D-AI/GarmageSet
---
