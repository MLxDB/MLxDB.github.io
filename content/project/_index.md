---
title: Projects
type: project
tags:
  - preface



banner:
  caption: ''
  image: ''
---

## Overview of Our Research

Our research focuses on **Data+AI**, bridging the gap between data management and artificial intelligence. We explore two main directions: **DB4AI** (Database for AI) and **AI4DB** (AI for Database).

{{< interactive_overview >}}

Below is a list of our specific projects and publications in these areas.

<span id="db4ai"></span>
## DB4AI
We design next-generation data systems tailored for AI applications, supporting multimodal data and complex analytical queries.

<span id="arcade-system"></span>
### Real-time AI-powered Multimodal Analytics System: ARCADE
- **[ARCADE: A Real-Time Data System for Hybrid and Continuous Query Processing across Diverse Data Modalities.]({{< ref "publication/icde26-arcade" >}})** (ICDE 2026) [[Code]](https://github.com/Jamesyang2333/ARCADE)

<span id="semantic-queries"></span>
### Semantic Queries & Data Agent
We build intelligent data agents and systems capable of handling semantic and analytical queries over heterogeneous data sources.
- **[CARROT: A Learned Cost-Constrained Retrieval Optimization System for RAG.]({{< ref "publication/icde26-carrot" >}})** (ICDE 2026) [[Code]](https://github.com/wang0702/CARROT)
- **[FDABench: A Benchmark for Data Agents on Analytical Queries over Heterogeneous Data.]({{< ref "publication/corr25-fdabench" >}})** (CoRR 2025) [[Code]](https://github.com/fdabench/FDAbench)

<span id="hybrid-search"></span>
### Hybrid Search
We develop efficient indexing and search algorithms to support hybrid queries over vector and relational data.
- **[DEG: Efficient Hybrid Vector Search Using the Dynamic Edge Navigation Graph.]({{< ref "publication/sigmod25-deg" >}})** (SIGMOD 2025)
- **[GeoBloom: Revisiting Lightweight Models for Geographic Information Retrieval.]({{< ref "publication/pvldb25-geobloom" >}})** (PVLDB 2025)

<span id="lsm-storage"></span>
### Multimodal LSM Storage
We optimize LSM-tree based storage engines to efficiently manage multimodal data on modern hardware.
- **[SOLAR: Efficient Spatial Queries on LSM-based Storage.]({{< ref "publication/icde26-solar" >}})** (ICDE 2026)
- **[NEXT: A New Secondary Index Framework for LSM-based Data Storage.]({{< ref "publication/sigmod25-next" >}})** (SIGMOD 2025)
- **[CAMAL: Optimizing LSM-trees via Active Learning.]({{< ref "publication/sigmod25-camal" >}})** (SIGMOD 2025)

<span id="ai4db"></span>
## AI4DB
We apply machine learning technqiues to enhance the performance and manageability of database systems.

<span id="query-optimization"></span>
### Query Optimization
We explore learning-based query optimization, focusing on cardinality estimation, plan representation, and rewrite systems to surpass traditional optimizers.
- **[RankPQO: Learning-to-Rank for Parametric Query Optimization.]({{< ref "publication/pvldb25-rankpqo" >}})** (PVLDB 2025)
- **[LLM-R2: A Large Language Model Enhanced Rule-based Rewrite System for Boosting Query Efficiency.]({{< ref "publication/pvldb25-llm-r2" >}})** (PVLDB 2025)
- **[Lemo: A Cache-Enhanced Learned Optimizer for Concurrent Queries.]({{< ref "publication/sigmod24-lemo" >}})** (SIGMOD 2024)

<span id="learned-index"></span>
### ML-enhanced Indexes
We investigate the design of learned index structures that adapt to data distribution and workload patterns for better efficiency.
- **[BT-Tree: A Reinforcement Learning Based Index for Big Trajectory Data.]({{< ref "publication/sigmod25-bttree" >}})** (SIGMOD 2025)
- **[MAAdvisor: Zero-Shot Index Advisor using Multi-Agent LLMs.]({{< ref "publication/corr25-maadvisor" >}})** (CoRR 2025)
- **[PLATON: Top-down R-tree Packing with Learned Partition Policy.]({{< ref "publication/sigmod24-platon" >}})** (SIGMOD 2024)
- **[The RLR-Tree: A Reinforcement Learning Based R-Tree for Spatial Data.]({{< ref "publication/sigmod23-rlr-tree" >}})** (SIGMOD 2023)

<span id="query-representation"></span>
### Query Representation Learning
We study how to effectively represent queries and plans for transfer learning and generalizability.
- **[TATA: An Efficient Framework for Task Transfer in Query Plan Representation.]({{< ref "publication/pvldb26-tata" >}})** (PVLDB 2026)
- **[QueryFormer: a tree transformer model for query plan representation.]({{< ref "publication/vldb22-query-former" >}})** (VLDB 2022)
