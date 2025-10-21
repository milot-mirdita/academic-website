---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Scaling down protein language modeling with MSA Pairformer
subtitle: ''
summary: ''
authors:
- Yo Akiyama
- Zhidian Zhang
- Milot Mirdita
- Martin Steinegger
- Sergey Ovchinnikov
tags: []
categories: []
date: '2025-01-01'
lastmod: 2025-10-14T03:34:32+09:00
featured: false
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
publishDate: '2025-10-13T18:34:32.201632Z'
publication_types:
- '2'
abstract: Recent efforts in protein language modeling have focused on scaling single-sequence
  models and their training data, requiring vast compute resources that limit accessibility.
  Although models that use multiple sequence alignments (MSA), such as MSA Transformer,
  offer parameter-efficient alternatives by extracting evolutionary information directly
  from homologous sequences rather than storing it in parameters, they generally underperform
  compared to single-sequence-based language due to memory inefficiencies that limit
  the number of sequences and averaging evolutionary signals across the MSA. We address
  these challenges with MSA Pairformer, a 111M parameter memory-efficient MSA-based
  protein language model that extracts evolutionary signals most relevant to a query
  sequence through bi-directional updates of sequence and pairwise representations.
  MSA Pairformer achieves state-of-the-art performance in unsupervised contact prediction,
  outperforming ESM2-15B by 6% points while using two orders of magnitude fewer parameters.
  In predicting contacts at protein-protein interfaces, MSA Pair-former substantially
  outperforms all methods with a 24% point increase over MSA Transformer. Unlike single-sequence
  models that deteriorate in variant effect prediction as they scale, MSA Pairformer
  maintains strong performance in both tasks. Ablation studies reveal triangle operations
  remove indirect correlations, and unlike MSA Transformer, MSA Pairformer does not
  hallucinate contacts after removing covariance, enabling reliable screening of interacting
  sequence pairs. Overall, our work presents an alternative to the current scaling
  paradigm in protein language modeling, enabling efficient adaptation to rapidly
  expanding sequence databases and opening new directions for biological discovery.
publication: '*bioRxiv*'
doi: 10.1101/2025.08.02.668173v1
---
