---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

## Routability-Driven Global Placement for VLSI

My current work studies routability optimization during analytical global placement.

- Built a heuristic optimization baseline based on early global routing and reproduced cell-inflation methods driven by early congestion estimation.
- Designed a congestion optimization model based on differentiable Steiner trees, transforming discrete congestion costs into continuous differentiable penalties for an analytical placement objective.
- Explored a framework that combines heuristic baselines and differentiable models to balance placement quality, optimization stability, and convergence efficiency under complex constraints.

## 3D Scene Rendering Optimization with Gaussian Splatting

- Designed an optimization pipeline for 3D Gaussian Splatting that introduces ZoeDepth depth estimation and SAM semantic segmentation as training priors.
- Developed a joint loss combining RGB, depth, and smoothness regularization to improve rendering quality and depth consistency.
- Conducted ablation studies on the WAT (World Across Time) dataset. The depth-smoothness constrained model improved PSNR compared with vanilla 3DGS.
