---
title: "DFCON: Attention-Driven Supervised Contrastive Learning for Robust Deepfake Detection"
authors:
- MD Sadik Hossain Shanto*
- Mahir Labib Dihan*
- Souvik Ghosh*
- Riad Ahmed Anonto*
- Hafijul Hoque Chowdhury*
- Abir Muhtasim*
- Rakib Ahsan*
- MD Tanvir Hassan*
- MD Roqunuzzaman Sojib*
- Sheikh Azizul Hakim†
- M. Saifur Rahman‡
date: "2025-01-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-28T00:00:00Z"

# Publication type.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "arXiv Preprint"
publication_short: "arXiv"

abstract: |
  This report presents our approach for the IEEE SP Cup 2025: Deepfake Face Detection in the Wild (DFWild-Cup), focusing on detecting deepfakes across diverse datasets. Our methodology employs advanced backbone models, including MaxViT, CoAtNet, and EVA-02, fine-tuned using supervised contrastive loss to enhance feature separation. These models were specifically chosen for their complementary strengths. After training, we freeze their parameters and train classification heads, combining predictions through a majority voting ensemble. The proposed system achieves a commendable accuracy of **95.83%** on the validation dataset, demonstrating robustness and generalization across diverse deepfake scenarios.

# Summary. An optional shortened abstract.
summary: "We propose DFCON, a supervised contrastive learning and ensemble-based approach for robust deepfake detection, achieving 95.83% validation accuracy in IEEE SP Cup 2025."

tags:
- Deepfake Detection
- Supervised Contrastive Learning
- Vision Transformers
- Ensemble Learning

featured: true

links:
- name: ArXiv
  url: https://arxiv.org/abs/2501.16704
url_pdf: https://arxiv.org/pdf/2501.16704v1
url_code: 'https://github.com/your-repo-link' # replace with your repo if available
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
image:
  caption: 'Proposed DFCON framework combining MaxViT, CoAtNet, and EVA-02 with supervised contrastive learning.'
  focal_point: ""
  preview_only: false

projects:
- internal-project

slides: ""
---

This work was developed as part of the IEEE SPS Signal Processing Cup 2025 competition (DFWild-Cup).  
We ensemble **MaxViT, CoAtNet, and EVA-02** backbones trained with **supervised contrastive loss**, applying extensive offline and online augmentation for robustness. The final ensemble achieved **state-of-the-art accuracy of 95.83%** on validation data.

{{% callout note %}}
Equal contribution by the first Nine authors.  
† Graduate Mentor · ‡ Supervisor
{{% /callout %}}
