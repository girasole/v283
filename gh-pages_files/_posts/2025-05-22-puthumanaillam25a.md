---
title: 'TAB-Fields: A Maximum Entropy Framework for Mission-Aware Adversarial Planning'
abstract: 'Autonomous agents operating in adversarial scenarios face a fundamental
  challenge: while they may know their adversaries’ high-level objectives, such as
  reaching specific destinations within time constraints, the exact policies these
  adversaries will employ remain unknown. Traditional approaches address this challenge
  by treating the adversary’s state as a partially observable element, leading to
  a formulation as a Partially Observable Markov Decision Process (POMDP). However,
  the induced belief-space dynamics in a POMDP require knowledge of the system’s transition
  dynamics, which, in this case, depend on the adversary’s unknown policy. Our key
  observation is that while an adversary’s exact policy is unknown, their behavior
  is necessarily constrained by their mission objectives and the physical environment,
  allowing us to characterize the space of possible behaviors without assuming specific
  policies. In this paper, we develop Task-Aware Behavior Fields (TAB-Fields), a representation
  that captures adversary state distributions over time by computing the most unbiased
  probability distribution consistent with known constraints. We construct TAB-Fields
  by solving a constrained optimization problem that minimizes additional assumptions
  about adversary behavior beyond mission and environmental requirements. We integrate
  TAB-Fields with standard planning algorithms by introducing TAB-conditioned POMCP,
  an adaptation of Partially Observable Monte Carlo Planning. Through experiments
  in simulation with underwater robots and hardware implementations with ground robots,
  we demonstrate that our approach achieves superior performance compared to baselines
  that either assume specific adversary policies or neglect mission constraints altogether.
  Evaluation videos and code are available at https://tab-fields.github.io.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: puthumanaillam25a
month: 0
tex_title: 'TAB-Fields: A Maximum Entropy Framework for Mission-Aware Adversarial
  Planning'
firstpage: 1484
lastpage: 1497
page: 1484-1497
order: 1484
cycles: false
bibtex_author: Puthumanaillam, Gokul and Song, Jae Hyuk and Yesmagambet, Nurzhan and
  Park, Shinkyu and Ornik, Melkior
author:
- given: Gokul
  family: Puthumanaillam
- given: Jae Hyuk
  family: Song
- given: Nurzhan
  family: Yesmagambet
- given: Shinkyu
  family: Park
- given: Melkior
  family: Ornik
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
pdf: https://raw.githubusercontent.com/mlresearch/v283/main/assets/puthumanaillam25a/puthumanaillam25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
