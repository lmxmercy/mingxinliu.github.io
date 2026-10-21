---
title:          Synergistic Information Disentanglement for Omni-modal Slide Representation Learning in Computational Pathology
date:           2026-05-08 00:01:00 +0800
selected:       true
pub:            "29th International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-custom badge-secondary">Conference</span>'
pub_last:       ' <span class="badge badge-pill badge-custom badge-secondary">Conference</span><span class="badge badge-pill badge-custom badge-success">Oral</span>'
pub_date:       "2026"

abstract: >-
   In computational pathology (CPath), developing omni-modal self-supervised learning (SSL) models that integrate histology, genomics, and clinical reports enables transferable representation learning for whole slide images (WSIs). 
   Existing approaches implicitly force heterogeneous modalities into a uniform latent space by contrastive alignment, causing modality collapse where unique, synergistic diagnostic signals (termed as Φ) are discarded in favor of trivial redundancy. 
   We hypothesize that the strongest task-agnostic SSL training signal stems from distilling the synergistic interactions over merely aligning shared redundancy. To this end, we introduce Φ-Omni, 
   a synergistic information disentanglement framework grounded in Partial Information Decomposition (PID) theory for slide representation learning. Unlike standard contrastive approaches, 
   Φ-Omni employs a Synergistic Information Bottleneck (SIB) regulated by the proposed ΦID objective, which explicitly suppresses marginal redundancy while maximizing irreducible synergy, thereby distilling highorder cross-modal interactions. 
   Following pretraining on breast (n=1031) and lung (n=919) cohorts, Φ-Omni demonstrates superior few-shot performance across five independent external datasets spanning eight tasks compared to supervised and SSL baselines. 

cover:          assets/images/covers/PhiOmni.png
authors:
  - Mingxin Liu
  - Chengfei Cai
  - Anwen Lu
  - Pengbo Xu
  - Jun Li
  - Jinze Li
  - Depin Chen
  - Jun Xu†
links:
  Paper: https://link.springer.com/chapter/10.1007/978-3-032-38224-5_49
  Code: https://github.com/lmxmercy/PhiOmni
  Poster: assets/slides/MICCAI2026-Phi-Omni-Poster.pdf
  Slides: assets/slides/MICCAI2026-Phi-Omni-Slides.pdf
  Cite: assets/bibtex/liu2026synergistic.bib
---
