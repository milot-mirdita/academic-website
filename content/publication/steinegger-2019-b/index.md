---
# Documentation: https://wowchemy.com/docs/managing-content/

title: HH-suite3 for fast remote homology detection and deep protein annotation.
subtitle: ''
summary: ''
authors:
- Martin Steinegger
- Markus Meier
- Milot Mirdita
- Harald Vöhringer
- Stephan J. Haunsberger
- Johannes Söding
tags:
- Algorithm
- Functional annotation
- Homology detection
- Profile HMM
- Protein alignment
- SIMD
- Sequence search
categories: []
date: '2019-09-01'
lastmod: 2023-12-16T19:48:03+09:00
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
publishDate: '2023-12-16T10:48:03.291212Z'
publication_types:
- '2'
abstract: BACKGROUND HH-suite is a widely used open source software suite for sensitive
  sequence similarity searches and protein fold recognition. It is based on pairwise
  alignment of profile Hidden Markov models (HMMs), which represent multiple sequence
  alignments of homologous proteins. RESULTS We developed a single-instruction multiple-data
  (SIMD) vectorized implementation of the Viterbi algorithm for profile HMM alignment
  and introduced various other speed-ups. These accelerated the search methods HHsearch
  by a factor 4 and HHblits by a factor 2 over the previous version 2.0.16. HHblits3
  is ∼10× faster than PSI-BLAST and ∼20× faster than HMMER3. Jobs to perform HHsearch
  and HHblits searches with many query profile HMMs can be parallelized over cores
  and over cluster servers using OpenMP and message passing interface (MPI). The free,
  open-source, GPLv3-licensed software is available at https://github.com/soedinglab/hh-suite
  . CONCLUSION The added functionalities and increased speed of HHsearch and HHblits
  should facilitate their use in large-scale protein structure and function prediction,
  e.g. in metagenomics and genomics projects.
publication: '*BMC Bioinformatics*'
doi: 10.1186/s12859-019-3019-7
links:
- name: URL
  url: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3019-7
    http://www.ncbi.nlm.nih.gov/pubmed/31521110 http://www.pubmedcentral.nih.gov/articlerender.fcgi?artid=PMC6744700
---
