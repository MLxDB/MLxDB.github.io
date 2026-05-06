---
title: Paper on Learned R-tree accepted at SIGMOD 2023
date: 2022-11-15
image:
  focal_point: 'top'
---

Congratulations to Gu Tu for publishing the paper "Effectively Learning Spatial Indexes with a Support for Updates" at SIGMOD 2023.
<!--more-->

Learned indices have been proposed to replace classic index structures like B-Tree with machine learning (ML) models. They require to replace both the indices and query processing algorithms currently deployed by the databases, and such a radical departure is likely to encounter challenges and obstacles. In contrast, we propose a fundamentally different way of using ML techniques to build a better R-Tree without the need to change the structure or query processing algorithms of traditional R-Tree. Specifically, we develop reinforcement learning (RL) based models to decide how to choose a subtree for insertion and how to split a node when building and updating an R-Tree, instead of relying on hand-crafted heuristic rules currently used by the R-Tree and its variants. Experiments on real and synthetic datasets with up to more than 100 million spatial objects show that our RL based index outperforms the R-Tree and its variants in terms of query processing time.