---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Petascale Homology Search for Structure Prediction
subtitle: ''
summary: ''
authors:
- Sewon Lee
- Gyuri Kim
- Eli Levy Karin
- Milot Mirdita
- Sukhwan Park
- Rayan Chikhi
- Artem Babaian
- Andriy Kryshtafovych
- Martin Steinegger
tags: []
categories: []
date: '2023-01-01'
lastmod: 2023-12-16T19:48:02+09:00
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
publishDate: '2023-12-16T10:48:02.662191Z'
publication_types:
- '2'
abstract: The recent CASP15 competition highlighted the critical role of multiple
  sequence alignments (MSAs) in protein structure prediction, as demonstrated by the
  success of the top AlphaFold2-based prediction methods. To push the boundaries of
  MSA utilization, we conducted a petabase-scale search of the Sequence Read Archive
  (SRA), resulting in gigabytes of aligned homologs for CASP15 targets. These were
  merged with default MSAs produced by ColabFold-search and provided to ColabFold-predict.
  By using SRA data, we achieved highly accurate predictions (GDT_TS &gt; 70) for
  66% of the non-easy targets, whereas using ColabFold-search default MSAs scored
  highly in only 52%. Next, we tested the effect of deep homology search and ColabFold's
  advanced features, such as more recycles, on prediction accuracy. While SRA homologs
  were most significant for improving ColabFold's CASP15 ranking from 11th to 3rd
  place, other strategies contributed too. We analyze these in the context of existing
  strategies to improve prediction.Competing Interest StatementThe authors have declared
  no competing interest.
publication: '*bioRxiv*'
doi: 10.1101/2023.07.10.548308
links:
- name: URL
  url: https://www.biorxiv.org/content/10.1101/2023.07.10.548308v1
---
