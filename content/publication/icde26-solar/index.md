---
title: "SOLAR: Efficient Spatial Queries on LSM-based Storage"
authors:
  - Jingyi Yang
  - Jiachen Shi
  - Jian Chen
  - Gao Cong
date: '2026-05-05T00:00:00Z'
publication: 'ICDE 2026'
publication_types: ['1']
abstract: "The burgeoning volumes of spatial data from location-based applications and GPS-enabled devices present unique challenges in spatial database design, necessitating both efficient data ingestion and query processing mechanisms. Existing Log-Structured Merge Tree (LSM-tree) based spatial databases, while adept at handling high-speed data ingestion, are less efficient for spatial queries as they adopt a general-purpose storage model and only support spatial queries as an afterthought. We introduce SOLAR, a novel LSM-based spatial data store tailored to achieve both rapid ingestion and fast spatial query processing. SOLAR treats spatial data as first-class citizens in its spatial-centric storage model, clustering the data by the spatial attributes in a single-LSM design. To enable efficient query processing on the new storage model, we design query processing algorithms that effectively prune away irrelavant LSM component files for both spatial range queries and KNN queries. Recognizing the challenge of increased write amplification due to the spatial-partitioned data layout, SOLAR implements a novel selective compaction framework, where compactions only involve a selected set of component files. This is supported by a cost model-based selection policy, optimizing query performance while ensuring low write amplification. Experiments on real-world datasets demonstrate the superior performance of SOLAR over existing LSM-based spatial systems and PostgreSQL across different dynamic workload scenarios."
featured: false
projects:
  - DB4AI
---
