---
title: "Symmetry-based Abstraction Algorithm for Accelerating Symbolic Control Synthesis"
collection: conference paper
permalink: /publication/2024-03-18-symmetry-based-abstraction-for-symbolic-control-synthesis
excerpt: 'An efficient symbolic control synthesis algorithm for equivariant continuous-time dynamical systems to satisfy reach-avoid specifications.'
date: 2024-03-18
venue: 'NASA Formal Methods'
paperurl: 'https://arxiv.org/abs/2403.11816'
citation: 'Sibai, Hussein, et al. "Symmetry-based Abstraction Algorithm for Accelerating Symbolic Control Synthesis." arXiv preprint arXiv:2403.11816 (2024).'
---

The algorithm exploits dynamical symmetries to construct lean abstractions to avoid redundant computations during synthesis. Our proposed algorithm adds another layer of abstraction over the common grid-based discrete abstraction before solving the synthesis problem. It combines each set of grid cells that are at a similar relative position from the targets and nearby obstacles, defined by the symmetries, into a single abstract state. It uses this layer of abstraction to guide the order by which actions are explored during synthesis over the grid-based abstraction. We demonstrate the potential of our algorithm by synthesizing a reach-avoid controller for a 3-dimensional ship model with translation and rotation symmetries in the special Euclidean group SE(2).
