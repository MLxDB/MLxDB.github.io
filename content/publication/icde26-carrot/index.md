---
title: "CARROT: A Learned Cost-Constrained Retrieval Optimization System for RAG"
authors:
  - Ziting Wang
  - Haitao Yuan
  - Wei Dong
  - Gao Cong
  - Feifei Li
date: '2026-05-05T00:00:00Z'
publication: 'ICDE 2026'
publication_types: ['1']
abstract: "Large Language Models (LLMs) have demonstrated impressive ability in generation and reasoning tasks but struggle with handling up-to-date knowledge, leading to inaccuracies or hallucinations. Retrieval-Augmented Generation (RAG) mitigates this by retrieving and incorporating external knowledge into input prompts. In particular, due to LLMs' context window limitations and long-context hallucinations, only the most relevant \"chunks\" are retrieved. However, current RAG systems face three key challenges: (1) chunks are often retrieved independently without considering their relationships, such as redundancy and orders; (2) the utility of chunks is non-monotonic, as adding more chunks can degrade quality; and (3) retrieval strategies fail to adapt to the unique characteristics of different queries. To overcome these challenges, we design a cost-constrained retrieval optimization framework for RAG. We adopt a Monte Carlo Tree Search (MCTS) based strategy to find the optimal chunk combination order, which considers the chunks' correlations. In addition, to address the non-monotonicity of chunk utility, instead of treating budget exhaustion as the termination condition, we design a utility computation strategy to identify the optimal chunk combination without necessarily exhausting the budget. Furthermore, we propose a configuration agent that predicts optimal configurations for each query domain, improving our framework's adaptability and efficiency. Experimental results demonstrate up to a 30% improvement over baseline models, highlighting the framework's effectiveness, scalability, and suitability."
featured: false
url_pdf: 'https://arxiv.org/abs/2411.00744'
url_code: 'https://github.com/wang0702/CARROT'
projects:
  - DB4AI
---
