---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'The OMG dataset: an open MetaGenomic corpus for mixed-modality genomic language
  modeling'
subtitle: ''
summary: ''
authors:
- Andre Cornman
- Jacob West-Roberts
- Antonio Pedro Camargo
- Simon Roux
- Martin Beracochea
- Milot Mirdita
- Sergey Ovchinnikov
- Yunha Hwang
tags: []
categories: []
date: '2024-01-01'
lastmod: 2025-10-14T03:34:31+09:00
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
publishDate: '2025-10-13T18:34:31.169566Z'
publication_types:
- '2'
abstract: Biological language model performance depends heavily on pretraining data
  quality, diversity, and size. While metagenomic datasets feature enormous biological
  diversity, their utilization as pretraining data has been limited due to challenges
  in data accessibility, quality filtering and deduplication. Here, we present the
  Open MetaGenomic (OMG) corpus, a genomic pretraining dataset totalling 3.1T base
  pairs and 3.3B protein coding sequences, obtained by combining two largest metagenomic
  dataset repositories (JGI’s IMG and EMBL’s MGnify). We first document the composition
  of the dataset and describe the quality filtering steps taken to remove poor quality
  data. We make the OMG corpus available as a mixed-modality genomic sequence dataset
  that represents multi-gene encoding genomic sequences with translated amino acids
  for protein coding sequences, and nucleic acids for intergenic sequences. We train
  the first mixed-modality genomic language model (gLM2) that leverages genomic context
  information to learn robust functional representations, as well as coevolutionary
  signals in protein-protein interfaces and genomic regulatory syntax. Furthermore,
  we show that deduplication in embedding space can be used to balance the corpus,
  demonstrating improved performance on downstream tasks. The OMG dataset is publicly
  hosted on the Hugging Face Hub at https://huggingface.co/datasets/tattabio/OMG and
  gLM2 is available at https://huggingface.co/tattabio/gLM2_650M.
publication: '*bioRxiv*'
doi: 10.1101/2024.08.14.607850v2
---
