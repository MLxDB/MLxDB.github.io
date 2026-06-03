---
title: "Demonstrating TOFFEE: A Learned System for Synthesizing Data Agent Trajectories at Scale"
authors:
  - Ziting Wang
  - Yin Li
  - Zuhao Yang
  - Xiuchang Li
  - Jiale Bai
  - Gao Cong
date: '2026-06-03T00:00:00Z'
publication: 'VLDB 2026 (Demonstration)'
publication_types: ['1']
abstract: "LLM-powered data agents are playing an increasingly important role in data-driven decision making. However, existing data agents struggle to generalize to unseen data environments and analytical workflows, particularly the diverse private ones prevalent in enterprises. This creates an urgent demand for synthesizing high-quality data agent trajectories that capture complex analytical workflows for given data environments. Such trajectories have broad downstream value: they serve as supervised finetuning (SFT) data that adapts data agent models to the target domain, and as in-context learning (ICL) demonstrations that guide general-purpose LLMs on unfamiliar data environments. Thus, we introduce TOFFEE, a learned system that synthesizes high-quality data agent trajectories from given data environments via Monte Carlo Tree Search (MCTS) with adaptive model selection and cross-task prefix reuse. We show that TOFFEE can effectively synthesize trajectories at scale, even for complex analytical tasks across heterogeneous data environments. In this demonstration, we present the system framework including the task synthesizer, trajectory explorer, and learned cost model. We introduce the web interface of TOFFEE and its workflow, and showcase end-to-end usage with two scenarios: trajectory synthesis for data agent finetuning, and demonstration-augmented data agent reasoning."
featured: false
image:
  caption: 'System overview of TOFFEE: task construction, trajectory exploration, and export of synthesized data agent trajectories for SFT or ICL.'
  focal_point: ''
  preview_only: false
projects:
  - DB4AI
---
