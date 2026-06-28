---
title:          Noise-Aware Importance-Uncertainty Disentangled Multimodal Learning for Robust Cancer Survival Prediction
date:           2026-06-18 00:01:00 +0800
selected:       true
pub:            "29th International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-custom badge-secondary">Conference</span>'
pub_date:       "2026"

abstract: >-
   Accurate cancer prognosis prediction from multimodal data is critical for personalized treatment planning, yet remains challenging due to modality-specific technical noise and heterogeneous prognostic characteristics. 
   In particular, whole slide images (WSIs) and mRNA expression profiles exhibit an overlooked asymmetry: WSIs provide stable but weak prognostic cues, whereas mRNA data offer strong prognostic relevance at the cost of high technical variability. 
   This discrepancy between technical uncertainty and prognostic importance is not explicitly modeled by existing multimodal survival models, leading to fragilecross-modal fusion. We introduce the Noise-Aware Disentangled Multimodal Survival Network (NADMSurv),
   a framework that formalizes importance–uncertainty asymmetry as a guiding principle for multimodal representation learning. An importance–uncertainty dual-track module jointly performs feature pre-selection and patient-level noise quantification 
   to encode heterogeneous prognostic patterns. A noise-aware disentanglement mechanism then separates multimodal representations into shared representations and modality-specific representations. 
   To model high-order patient correlations, hypergraph neural networks are employed, and subjective logic is introduced to generate opinions with uncertainty quantification, ultimately achieving evidence-level fusion through cross attention and 
   consensus operators. Multi-cohort evaluation on TCGA datasets demonstrates consistent improvements in C-index over state-of-the-art methods. By analyzing modality-specific technical noise characteristics and disentangling the importance–uncertainty asymmetry, 
   NADMSurv establishes a principled paradigm for robust multimodal survival prediction.

cover:          assets/images/covers/nadmsurv.png
authors:
  - Wenlong Ming
  - Wenbin Ye
  - Mingxin Liu
  - Depin Chen
  - Yiping Jiao
  - Jun Xu
  - Xiangxue Wang†
links:
---
