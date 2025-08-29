---
title: "ResLysEmbed: A ResNet-Based Framework for Succinylated Lysine Residue Prediction Using Sequence and Language Model Embeddings"
authors:
- admin
- Md Muhaiminul Islam Nafi
- M Saifur Rahman
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-01-01T00:00:00Z"
doi: "10.1093/bioadv/vbaf198"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-15T00:00:00Z"

# Publication type.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Bioinformatics Advances*"
publication_short: "*Bioinform Adv*"

abstract: |
  Lysine (K) succinylation is a crucial post-translational modification linked to diverse biological processes and diseases. Current computational methods remain limited in predictive power and interpretability. We present **ResLysEmbed**, a novel hybrid ResNet-based framework that integrates traditional word embeddings with protein language model embeddings (ProtT5) for succinylation site prediction. ResLysEmbed consistently outperforms existing methods, achieving accuracy, MCC, and F1-scores of 0.81/0.39/0.40 and 0.72/0.44/0.67 on two independent test sets, respectively. Comparative evaluations against other PLMs (PTM-Mamba, ESM-650M, ESM-3B) demonstrate ProtT5 as the most effective embedding choice. Furthermore, SHAP-based interpretability analysis reveals biologically meaningful insights into residue contributions within a 33-mer sequence window, reaffirming the biological relevance of our predictions. ResLysEmbed thus establishes itself as a robust and computationally efficient framework for lysine succinylation prediction.

summary: |
  We developed **ResLysEmbed**, a ResNet+MLP-based hybrid model that integrates word and protein language model embeddings to predict lysine succinylation sites with superior accuracy and interpretability. It outperforms existing methods and provides biologically relevant insights through SHAP analysis.

tags:
- Bioinformatics
- Proteomics
- Protein Language Models
- Post-translational Modifications
- Machine Learning
featured: true

url_pdf: "https://academic.oup.com/bioinformaticsadvances/advance-article/doi/10.1093/bioadv/vbaf198/8239949"
url_code: "https://github.com/Sheldor7701/ResLysEmbed"
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

image:
  caption: 'How Succinylation works'
  focal_point: "center"
  preview_only: false

projects: []

slides: ""
---

{{% callout note %}}
Click the *Cite* button above to import this publication into your reference manager.
{{% /callout %}}

{{% callout note %}}
This work introduces a new hybrid ResNet-based model for succinylation prediction, integrates multiple PLM embeddings, and applies SHAP analysis for biological interpretability.
{{% /callout %}}
