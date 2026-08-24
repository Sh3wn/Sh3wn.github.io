---
title: "ICCAD Contest 2024 Problem A"
excerpt: "An automated logic-netlist optimization flow built around ABC and a black-box cost estimator."
collection: portfolio
date: 2024-09-01
---

I built an ABC-based automated optimization flow for logic-netlist optimization and designed an evaluation framework around the contest's black-box cost estimator.

- Constructed a logic-synthesis action space for reinforcement learning and explored transformations including `resub`, `rewrite`, `refactor`, and `balance`.
- Designed and implemented Genlib Maker to convert the official JSON cell library into ABC-compatible `.genlib` and `.lib` inputs.
- Improved search efficiency through incremental iterative optimization.

**Technologies:** ABC, C++, Python, reinforcement learning, logic synthesis
