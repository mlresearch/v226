---
title: Planning By Active Sensing
abstract: Flexible behavior requires rapid planning, but planning requires a good
  internal model of the environment. Learning this model by trial-and-error is impractical
  when acting in complex environments. How do humans plan action sequences efficiently
  when there is uncertainty about model components? To address this, we asked human
  participants to navigate complex mazes in virtual reality. We found that the paths
  taken to gather rewards were close to optimal even though participants had no prior
  knowledge of these environments. Based on the sequential eye movement patterns observed
  when participants mentally compute a path before navigating, we develop an algorithm
  that is capable of rapidly planning under uncertainty by active sensing i.e., visually
  sampling information about the structure of the environment. ew eye movements are
  chosen in an iterative manner by following the gradient of a dynamic value map which
  is updated based on the previous eye movement, until the planning process reaches
  convergence. In addition to bearing hallmarks of human navigational planning, the
  proposed algorithm is sample-efficient such that the number of visual samples needed
  for planning scales linearly with the path length regardless of the size of the
  state space.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lakshminarasimhan24a
month: 0
tex_title: Planning By Active Sensing
firstpage: 125
lastpage: 141
page: 125-141
order: 125
cycles: false
bibtex_author: Lakshminarasimhan, Kaushik and Zhu, Seren and Angelaki, Dora
author:
- given: Kaushik
  family: Lakshminarasimhan
- given: Seren
  family: Zhu
- given: Dora
  family: Angelaki
date: 2024-04-24
address:
container-title: Proceedings of The 2nd Gaze Meets ML workshop
volume: '226'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 4
  - 24
pdf: https://proceedings.mlr.press/v226/lakshminarasimhan24a/lakshminarasimhan24a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v226/lakshminarasimhan24a/lakshminarasimhan24a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
