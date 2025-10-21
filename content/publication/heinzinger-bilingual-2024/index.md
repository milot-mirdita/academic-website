---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Bilingual language model for protein sequence and structure
subtitle: ''
summary: ''
authors:
- Michael Heinzinger
- Konstantin Weissenow
- Joaquin Gomez Sanchez
- Adrian Henkel
- Milot Mirdita
- Martin Steinegger
- Burkhard Rost
tags: []
categories: []
date: '2024-09-01'
lastmod: 2025-10-14T03:34:28+09:00
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
publishDate: '2025-10-13T18:34:28.354129Z'
publication_types:
- '2'
abstract: Adapting language models to protein sequences spawned the development of
  powerful protein language models (pLMs). Concurrently, AlphaFold2 broke through
  in protein structure prediction. Now we can systematically and comprehensively explore
  the dual nature of proteins that act and exist as three-dimensional (3D) machines
  and evolve as linear strings of one-dimensional (1D) sequences. Here, we leverage
  pLMs to simultaneously model both modalities in a single model. We encode protein
  structures as token sequences using the 3Di-alphabet introduced by the 3D-alignment
  method Foldseek. For training, we built a non-redundant dataset from AlphaFoldDB
  and fine-tuned an existing pLM (ProtT5) to translate between 3Di and amino acid
  sequences. As a proof-of-concept for our novel approach, dubbed Protein ‘structure-sequence’
  T5 (ProstT5), we showed improved performance for subsequent, structure-related prediction
  tasks, leading to three orders of magnitude speedup for deriving 3Di. This will
  be crucial for future applications trying to search metagenomic sequence databases
  at the sensitivity of structure comparisons. Our work showcased the potential of
  pLMs to tap into the information-rich protein structure revolution fueled by AlphaFold2.
  ProstT5 paves the way to develop new tools integrating the vast resource of 3D predictions
  and opens new research avenues in the post-AlphaFold2 era.
publication: '*NAR Genomics and Bioinformatics*'
doi: 10.1093/nargab/lqae150
links:
- name: URL
  url: https://academic.oup.com/nargab/article/doi/10.1093/nargab/lqae150/7901286
---
