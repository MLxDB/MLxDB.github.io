---
title: 'A Comparative Study and Component Analysis of Query Plan Representation Techniques in ML4DB Studies'
authors:
  - Yue Zhao
  - Zhaodonghui Li
  - Gao Cong

date: '2024-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 'Proceedings of the VLDB Endowment, Vol. 17, No. 4'
publication_short: 'VLDB 2024'

abstract: "Query plan is widely used as input in machine learning for databases (ML4DB) research, with query plan representation as a critical step. However, existing studies typically focus on one task, and propose a novel design to represent query plans along with a ML4DB framework, without comparing with other representation methods designed for a different task. This raises a critical question: How do we select a query plan representation method in a ML4DB system?

To address this question, we perform a comparative study on ten representation methods on three distinct ML4DB tasks: cost estimation, index selection and query optimization. Our extensive experiments not only verify the interchangeability of representation methods across different tasks, but also identify consistently high-performing models. Further, we dissect the query plan representation into two core components: feature encoding and tree model, and evaluate the impact of design choices for each in different scenarios. Our results show that the findings for tasks optimizing absolute errors are different from findings for tasks optimizing relative errors. Some findings challenge widely-held assumptions, i.e., one finding shows that tree models do not significantly impact cost estimation results, but only play a significant role to optimize relative performance. Practical guidelines and future directions are provided based on the findings of the study."

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/10.14778/3636218.3636235
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

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
