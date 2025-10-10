---
title: Automated Task Scheduling for Cloth and Deformable Body Simulations in Heterogeneous
  Computing Environments
authors:
- Chengzhu He
- Zhendong Wang
- Zhaorui Meng
- Junfeng Yao
- Shihui Guo
- admin
date: '2025-08-10'
publishDate: '2025-05-13T06:24:55.254008Z'
publication_types:
- paper-conference
publication: '*ACM SIGGRAPH 2025 Conference Papers*'

abstract: The concept of the Internet of Things (IoT) has driven the development of
  system-on-a-chip (SoC) technology for embedded and mobile systems, which may define
  the future of next-generation computation. In SoC devices, efficient cloth and deformable
  body simulations require parallelized, heterogeneous computation across multiple
  processing units. The key challenge in heterogeneous computation lies in task distribution,
  which must account for varying inter-task dependencies and communication costs.
  This paper proposes a novel framework for automated task scheduling to optimize
  simulation performance by minimizing communication overhead and aligning tasks with
  the specific strengths of each device. To achieve this, we introduce an efficient
  scheduling method based on the Heterogeneous Earliest Finish Time (HEFT) algorithm,
  adapted for hybrid systems. We model simulation tasks—such as those in iterative
  methods like Jacobi and Gauss-Seidel—as a Directed Acyclic Graph (DAG). To maximize
  the parallelism of nonlinear Gauss-Seidel simulation tasks, we present an innovative
  asynchronous Gauss-Seidel method with specialized data synchronization across units.
  Additionally, we employ task merging and tailored task-sorting strategies for Gauss-Seidel
  tasks to achieve an optimal balance between convergence and efficiency. We validate
  the effectiveness of our framework across various simulations, including XPBD, vertex
  block descent, and second-order stencil descent, using Apple M-series processors
  with both CPU and GPU cores. By maximizing computational efficiency and reducing
  processing times, our method achieves superior simulation frame rates compared to
  approaches that rely on individual devices in isolation. The source code with hybrid
  Metal/C++ implementation is available at https://github.com/ChengzhuUwU/libAtsSim.
summary: This paper proposes a novel framework for automated task scheduling to optimize
  simulation performance by minimizing communication overhead and aligning tasks with
  the specific strengths of each device.
tags:
- task scheduling
- heterogeneous computing
- asynchronous parallelism
links:
url_video: https://drive.google.com/file/d/1npHDiuVQhsj5K8eWrAcZrmetzEU3EeHL/view?usp=sharing
url_code: https://github.com/ChengzhuUwU/libAtsSim
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/ZIlrmXYL0PM?si=ukWUQRhHpTNblP9u" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=114499029894525&bvid=BV1Uo7Zz3EXn&cid=29936127582&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
