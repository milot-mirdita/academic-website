---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Foldcomp: a library and format for compressing and indexing large protein
  structure sets'
subtitle: ''
summary: ''
authors:
- Hyunbin Kim
- Milot Mirdita
- Martin Steinegger
tags: []
categories: []
date: '2023-04-01'
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
publishDate: '2023-12-16T10:48:02.536529Z'
publication_types:
- '2'
abstract: SUMMARY Highly accurate protein structure predictors have generated hundreds
  of millions of protein structures; these pose a challenge in terms of storage and
  processing. Here, we present Foldcomp, a novel lossy structure compression algorithm,
  and indexing system to address this challenge. By using a combination of internal
  and Cartesian coordinates and a bi-directional NeRF-based strategy, Foldcomp improves
  the compression ratio by a factor of three compared to the next best method. Its
  reconstruction error of 0.08 Å is comparable to the best lossy compressor. It is
  five times faster than the next fastest compressor and competes with the fastest
  decompressors. With its multi-threading implementation and a Python interface that
  allows for easy database downloads and efficient querying of protein structures
  by accession, Foldcomp is a powerful tool for managing and analysing large collections
  of protein structures. AVAILABILITY AND IMPLEMENTATION Foldcomp is a free open-source
  software (GPLv3) and available for Linux, macOS, and Windows at https://foldcomp.foldseek.com.
  Foldcomp provides the AlphaFold Swiss-Prot (2.9GB), TrEMBL (1.1TB), and ESMatlas
  HQ (114GB) database ready-for-download.
publication: '*Bioinformatics*'
doi: 10.1093/bioinformatics/btad153
links:
- name: URL
  url: 
    https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btad153/7085592
---
