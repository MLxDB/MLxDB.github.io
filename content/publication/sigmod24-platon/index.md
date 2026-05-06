---
title: 'PLATON: Top-down R-tree Packing with Learned Partition Policy'
authors:
  - Jingyi Yang
  - Gao Cong 


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

abstract: The exponential growth of spatial data poses new challenges to the performance of spatial databases. Spatial indexes like R-tree greatly accelerate the query performance and can be effectively constructed through packing, i.e., loading all data into the index at once. However, existing R-tree packing methods rely on a set of fixed heuristic rules, which may not be suitable for different data distributions and workload patterns. To address the limitations of existing R-tree packing methods, we propose PLATON, a top-down R-tree packing method with learned partition policy that explicitly optimizes the query performance with regard to the given data and workload instance. We develop a learned partition policy based on Monte Carlo Tree Search and carefully make design choices for the MCTS exploration strategy and simulation strategy to improve algorithm convergence. We propose a divide and conquer strategy and two optimization techniques, early termination and level-wise sampling, to drastically reduce the MCTS algorithm’s time complexity and make it a linear-time algorithm. Experiments on both synthetic and real-world datasets demonstrate the superior performance of PLATON over existing R-tree variants and recently proposed learned/workload-aware spatial indexes.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# links:
#   - name: Custom Link
#     url: http://example.org
url_pdf: 
url_code: 
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).
