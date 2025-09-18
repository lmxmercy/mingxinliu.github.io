---
title:          SC-AGR：Spatially-Constrained Attention for Context-Aware Graph Representation in Histopathology Whole Slide Image Analysis
date:           2025-07-17 00:01:00 +0800
selected:       true
pub:            "International Conference on Intelligent Computing (ICIC)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-custom badge-secondary">Conference</span>'
pub_date:       "2025"

abstract: >-
  Whole-slide images (WSIs) are widely used in histopathological examination, but current multi-instance learning (MIL) methods often fail to capture the complex interactions between instances in a WSI. Existing graph-based approaches, while modeling spatial relationships, are limited in their ability to capture interactions across arbitrary distances. We proposed a Spatially-Constrained Attention for Context-Aware Graph Representation framework (SC-AGR) to address these limitations. Specifically: 1) We introduce a context-aware graph representation that dynamically constructs spatial associations between different regions in a WSI, thereby more accurately capturing the characteristics of lesion tissue; 2) A spatially constrained attention mechanism enhances feature learning by aggregating adjacent nodes, allowing key patches to propagate information and improve WSI analysis; 3) We combined graph convolutional network (GCN) layers with instance clustering to further refine and constrain the graph representation feature space, boosting the model’s performance and data efficiency. Extensive experiments conducted on three public datasets demonstrate that SC-AGR outperformed state-of-the-art (SOTA) WSI analysis methods.
  
cover:          assets/images/covers/icic.png
authors:
  - Chengfei Cai
  - Jiahao Chen
  - Mingxin Liu
  - Jun Li
  - Jun Xu†
links:
  Paper: https://link.springer.com/chapter/10.1007/978-981-95-0027-7_11
  Code: https://github.com/caicai2526/SC-AGR
  Cite: assets/bibtex/cai2025sc.bib
---
