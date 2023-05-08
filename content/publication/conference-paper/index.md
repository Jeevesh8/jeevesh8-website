---
abstract: "It is widely accepted in the mode connectivity literature that when
  two neural networks are trained similarly on the same data, they are connected
  by a path through parameter space over which test set accuracy is maintained.
  Under some circumstances, including transfer learning from pretrained models,
  these paths are presumed to be linear. In contrast to existing results, we
  find that among text classifiers (trained on MNLI, QQP, and CoLA), some pairs
  of finetuned models have large barriers of increasing loss on the linear paths
  between them. On each task, we find distinct clusters of models which are
  linearly connected on the test loss surface, but are disconnected from models
  outside the cluster -- models that occupy separate basins on the surface. By
  measuring performance on specially-crafted diagnostic datasets, we find that
  these clusters correspond to different generalization strategies: one cluster
  behaves like a bag of words model under domain shift, while another cluster
  uses syntactic heuristics. Our work demonstrates how the geometry of the loss
  surface can guide models towards different heuristic functions."
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Jeevesh Juneja
  - Rachit Bansal
  - Kyunghyun Cho
  - João Sedoc
  - Naomi Saphra
author_notes: []
publication: In *International Conference on Learning Representations* 2023
summary: We find a population of models that has two linearly disconnected
  clusters of models. The models in a single cluster are all linearly connected,
  and exhibit similar OOD behavior. Also, the clusters trap training
  trajectories.
url_dataset: https://github.com/wowchemy/wowchemy-hugo-themes
url_project: ""
publication_short: In *ICLR* 2023
url_source: https://github.com/wowchemy/wowchemy-hugo-themes
url_video: https://youtube.com
title: Linear Connectivity Reveals Generalization Strategies
doi: https://doi.org/10.48550/arXiv.2205.12411
featured: true
tags: []
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
---
