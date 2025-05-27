---
title: 'STRiDE: STate-space Riemannian Diffusion for Equivariant Planning'
abstract: Fast and reliable motion planning is essential for robots with many degrees
  of freedom in complex, dynamic environments. Diffusion models offer a promising
  alternative to classical planners by learning informative trajectory priors. In
  current imitation-learning paradigms, these models are kept lightweight—lacking
  encoders—and trained to overfit to a single environment. As a result, adaptation
  relies solely on diffusion guidance, which fails under large execution-time changes
  or varying initializations. In addition, current approaches ignore the underlying
  topology of the state space thus requiring heavy guidance that dominates planning
  time and reduces efficiency dramatically. We introduce STRiDE, a novel diffusion
  motion planner that operates directly on the state space manifold and learns equivariant
  trajectory priors. Our approach eliminates the need for retraining under rotations
  around the gravity axis and enables faster convergence using Riemannian (rather
  than ambient) guidance. STRiDE delivers efficient, robust, and generalizable planning,
  overcoming key limitations of existing approaches.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chatzipantazis25a
month: 0
tex_title: 'STRiDE: STate-space Riemannian Diffusion for Equivariant Planning'
firstpage: 1338
lastpage: 1352
page: 1338-1352
order: 1338
cycles: false
bibtex_author: Chatzipantazis, Evangelos and Rao, Nishanth and Daniilidis, Kostas
author:
- given: Evangelos
  family: Chatzipantazis
- given: Nishanth
  family: Rao
- given: Kostas
  family: Daniilidis
date: 2025-05-22
address:
container-title: Proceedings of the 7th Annual Learning for Dynamics \& Control Conference
volume: '283'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 5
  - 22
pdf: https://raw.githubusercontent.com/mlresearch/v283/main/assets/chatzipantazis25a/chatzipantazis25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
