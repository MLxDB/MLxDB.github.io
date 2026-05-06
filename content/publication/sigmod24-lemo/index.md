---
title: 'Lemo: A Cache-Enhanced Learned Optimizer for Concurrent Queries'
authors:
  - Song Song Mo
  - Yile Chen
  - Hao Wang
  - Gao Cong
  - Zhifeng Bao
date: '2023-08-26T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-26T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 2024 International Conference on Management of Data
publication_short: SIGMOD 2024

abstract: With the expansion of modern database services, multi-user access has become a crucial feature in various practical application scenarios, including enterprise applications and e-commerce platforms. However, if multiple users submit queries within a short time frame, it can result in potential issues such as redundant computation and query concurrency. Unfortunately, most existing multi-query optimization methods, which aim to enhance query processing efficiency, have not adequately addressed these two problems, especially in the setting where multiple queries are being executed concurrently. To this end, we propose a novel method named Lemo for the multi-query optimization problem. Specifically, we propose a novel value network to predict latencies of concurrent queries as the foundation model for query plan generation. Furthermore, we introduce a shared buffer manager component to cache the intermediate results of sub-queries. The shared buffer manager applies a novel replacement policy to maintain the cached buffer with the objective of maximizing the opportunity for the reuse of the cached sub-queries. Based on the shared buffer, our proposed value network can incorporate the cached results into cost estimation to further guide Lemo in generating query plans, thus avoiding redundant computation. Lemo has been integrated into PostgreSQL and experiments conducted on real datasets with PostgreSQL show that it outperforms all the baselines in efficiency.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: false

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: 
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).
