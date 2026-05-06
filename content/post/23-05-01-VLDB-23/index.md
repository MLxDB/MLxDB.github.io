---
title: Paper on Learned Space-Filling Curve accepted at VLDB 2023
date: 2023-05-01
image:
  focal_point: 'top'
---

Congratulations to Jiangneng for publishing the paper "Towards Designing and Learning Piecewise Space-Filling Curves" at VLDB 2023.
<!--more-->

To index multi-dimensional data, space-filling curves (SFCs) have
been used to map the data to one dimension, and then a one dimensional indexing method such as the B-tree is used to index the mapped data. The existing SFCs all adopt a single mapping scheme for the whole data space. However, a single mapping scheme often does not performwell on all the data space. In this paper,we propose a new type of SFC called piecewise SFCs, which adopts different mapping schemes for different data subspaces. Specifically, we propose a data structure called Bit Merging tree (BMTree), which can generate data subspaces and their SFCs simultaneously and achieve desirable properties of the SFC for the whole data space. Furthermore, we develop a reinforcement learning based solution to build the BMTree, aiming to achieve excellent query performance. Extensive experiments show that our proposed method outperforms existing SFCs in terms of query performance.