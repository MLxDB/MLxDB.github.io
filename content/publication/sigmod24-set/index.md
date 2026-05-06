---
title: 'Selectivity Estimation for Queries Containing Predicates over Set-Valued Attributes'
authors:
  - Zizhong Meng
  - Xin Cao
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

abstract: Selectivity estimation aims to estimate the size of query results size accurately and efficiently. Despite being a well-researched area for decades, most existing estimators are designed to handle comparison predicates over numeric and categorical data. Nevertheless, Set-valued data are ubiquitous in many applications such as information retrieval and recommendation systems. However, these estimators may not be effective for handling predicates over set-valued data. In this work, we presents novel techniques for selectivity estimation on queries involving predicates over set-valued attributes. We first propose the set-valued column factorization problem, whereby each each set-valued column is converted to multiple numeric subcolumns, and set containment predicates are converted to numeric comparison predicates. This enables us to leverage any existing estimator to perform selectivity estimation. We then develop two methods for column factorization and query conversion, namely ST and ST-hist. We integrate ST and ST-hist into three estimators, Postgres, Neurocard, and DeepDB. We then conduct a comprehensive empirical analysis by comparing our approach against three baselines across three different datasets. The experimental results demonstrate that our methods exhibit superior estimation accuracy while maintaining high efficiency compared to the baseline techniques.

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
