---
featured: false
title: Interactive Yarn-level Knitwear with Nested Douglas-Rachford Splitting
authors:
- Chun Yuan
- Zixuan Lu
- Haoyang Shi
- Dewen Guo
- admin
- Chenfanfu Jiang
- Zherong Pan
- Kui Wu
- Yin Yang
date: '2026-08-01'
publishDate: '2026-06-16T00:00:00Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH), 45*(4)'
tags:
- knitwear simulation
- yarn-level simulation
- douglas-rachford splitting
doi: "10.1145/3811277"
summary: "We enable interactive yarn-level knitwear simulation with nested Douglas-Rachford splitting. Decomposing yarn mechanics and contact into convex subproblems supports robust, matrix-free GPU simulation with millions of degrees of freedom."
abstract: "While yarn-level garments offer rich dynamic details and compelling visual realism compared to triangle-based models, their wide adoption is hindered by the immense computational cost due to the presence of a large number of degrees of freedom (DOFs). This paper proposes a novel simulation framework designed to enhance the performance and stability for numerical simulation of nonlinear, non-convex, and high-resolution knitwear. Our method generalizes the Douglas-Rachford Splitting (DRS) scheme to resolve the non-convex coupling between stretching, shearing, bending, twisting, and contacting at each yarn thread. A key contribution is a nested decomposition strategy that decouples the non-convex variational energy into independent and convex sub-problems. Such convexification improves solver robustness and removes the necessity for frequent line searches. We provide a theoretically grounded strategy for metric selection for each sub-problem, derived from an analysis of the convergence guarantee of DRS. Consequently, our method achieves close-to-optimal convergence along the nonlinear iterations rather than relying on ad-hoc parameter tuning. The paper also clarifies a formal connection between our generalized DRS and the ADMM (Alternating Direction Method of Multipliers) framework, extending the applicability of our analysis to a broader set of constrained dynamics problems. Experimental results demonstrate that our method robustly handles complex knitwear simulation scenes with superior efficiency, stability, and physical fidelity compared to existing methods. With a matrix-free GPU parallelization, our method allows an interactive simulation rate of knitwear of multi-million DOFs."
---
