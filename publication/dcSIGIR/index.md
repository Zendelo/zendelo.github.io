---
# Documentation: https://wowchemy.com/docs/managing-content/

title: New Perspectives to Query Performance Prediction Evaluation
subtitle: ''
summary: ''
authors:
- admin
tags:
- '"Query Performance Prediction"'
- '"Evaluation"'
- '"Query Variations"'
categories: []
date: '2021-05-10'
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

publication_types: ["1"]
abstract: 'The research on Query Performance Prediction (QPP) focuses on
  estimating the effectiveness of retrieval results in the absence of human relevance judgments.
  Accurately estimating the result of a search performed in response to a query has been extensively studied over the past two decades.
  With the rising popularity of virtual assistants along with evolving research on complex informa- tion needs,
  the need for reliable QPP methods as well as the number of potential applications significantly increases.
  In this work, we focus on improving the evaluation framework of QPP.
  As we see the existing evaluation as a considerable limitation in the improvement of QPP methods,
  a reliable and improved evaluation framework would constitute a stepping-stone for a breakthrough in QPP.
  The existing evaluation framework in QPP mainly relies on the
  measurement of the correlation coefficient between the per-query
  prediction scores and the actual per-query system effectiveness
  measure, usually Average Precision (AP). The QPP method that
  achieves higher correlation is considered to be superior. However,
  Hauff et al. demonstrate that higher correlation does not vouch
  for more accurate prediction. The authors additionally advocate the
  usage of Fisher’s 𝑧 transformation and Confidence Intervals (CIs)
  to determine statistically significant differences between multiple
  correlation coefficients. Furthermore, the existing evaluation
  methodology is true only per a specific combination of a corpus,
  retrieval method, and set of queries; and does not necessarily hold
  if any of these is changed. That is, the existing evaluation
  is not agnostic to the different components, thus any conclusions
  about the relative prediction quality of the QPP methods should be
  taken with a grain of salt.
  '
  

publication: '*Proceedings of the 44th International ACM SIGIR Conference on Research
  and Development in Information Retrieval*'
doi: 10.1145/3404835.3463270?cid=99659451812

publication_short: In *SIGIR'21*

---
