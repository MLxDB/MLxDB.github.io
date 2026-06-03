---
title: "ARCADE: A Real-Time Data System for Hybrid and Continuous Query Processing across Diverse Data Modalities"
authors:
  - Jingyi Yang
  - Songsong Mo
  - Jiachen Shi
  - Zihao Yu
  - Kunhao Shi
  - Xuchen Ding
  - Gao Cong
date: '2026-06-03T00:00:00Z'
publication: 'VLDB 2026 Demonstration'
publication_types: ['1']
abstract: "The explosive growth of multimodal data spanning text, spatial, vector, and relational modalities, coupled with the need for real-time semantic search and retrieval, has outpaced the capabilities of existing systems, which either lack efficient ingestion and continuous query capabilities, or fall short in supporting expressive hybrid analytics. We introduce ARCADE, a real-time data system that efficiently supports high-throughput ingestion and expressive hybrid and continuous query processing across diverse data types. ARCADE introduces a unified disk-based secondary index framework on LSM-based storage for vector, spatial, and text data modalities, a comprehensive cost-based query optimizer that jointly leverages multiple heterogeneous indexes for hybrid queries, and an incremental materialized view framework for efficient continuous queries. ARCADE is built on open-source RocksDB and MySQL, with comprehensive system design and experiments presented in our ICDE 2026 research paper. Our demonstration showcases ARCADE through interactive real-world scenarios of social media marketing and equity research, exposing system-level metrics, internal query optimization decisions, and side-by-side baseline comparisons to provide attendees with deep insights into how ARCADE's architectural choices facilitate real-time multimodal analytics."
url_code: 'https://github.com/Jamesyang2333/ARCADE'
featured: false
image:
  caption: 'System architecture of ARCADE: query interface, query processing, and storage layers over a unified disk-based secondary index on LSM storage.'
  focal_point: ''
  preview_only: false
projects:
  - DB4AI
---
