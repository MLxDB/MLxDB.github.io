---
title: Paper on selectivity estimation for set-valued data accepted at SIGMOD 2024
date: 2023-08-26
image:
  focal_point: 'top'
---

Congratulations to Zizhong for publishing the paper "Selectivity Estimation for Queries Containing Predicates over Set-Valued Attributes" at SIGMOD 2024.
<!--more-->

Selectivity estimation aims to estimate the size of query results size accurately and efficiently. Despite being a well-researched area for decades, most existing estimators are designed to handle comparison predicates over numeric and categorical data. Nevertheless, Set-valued data are ubiquitous in many applications such as information retrieval and recommendation systems. However, these estimators may not be effective for handling predicates over set-valued data. In this work, we presents novel techniques for selectivity estimation on queries involving predicates over set-valued attributes. We first propose the set-valued column factorization problem, whereby each each set-valued column is converted to multiple numeric subcolumns, and set containment predicates are converted to numeric comparison predicates. This enables us to leverage any existing estimator to perform selectivity estimation. We then develop two methods for column factorization and query conversion, namely ST and ST-hist. We integrate ST and ST-hist into three estimators, Postgres, Neurocard, and DeepDB. We then conduct a comprehensive empirical analysis by comparing our approach against three baselines across three different datasets. The experimental results demonstrate that our methods exhibit superior estimation accuracy while maintaining high efficiency compared to the baseline techniques.