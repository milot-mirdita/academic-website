---
# Documentation: https://wowchemy.com/docs/managing-content/

title: TransAnnot—a fast transcriptome annotation pipeline
subtitle: ''
summary: ''
authors:
- Mariia Zelenskaia
- Yazhini Arangasamy
- Milot Mirdita
- Johannes Söding
- Venket Raghavan
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
publishDate: '2025-10-13T18:34:31.488285Z'
publication_types:
- '2'
abstract: The annotation of deeply sequenced, de novo assembled transcriptomes continues
  to be a challenge as some of the state-of-the-art tools are slow, difficult to install,
  and hard to use. We have tackled these issues with TransAnnot, a fast, automated
  transcriptome annotation pipeline that is easy to install and use. Leveraging the
  fast sequence searches provided by the MMseqs2 suite, TransAnnot offers one-step
  annotation of homologs from Swiss-Prot, gene ontology terms and orthogroups from
  eggNOG, and functional domains from Pfam. Users also have the option to annotate
  against custom databases. TransAnnot accepts sequencing reads (short and long),
  nucleotide sequences, or amino acid sequences as input for annotation. When benchmarked
  with test data sets of amino acid sequences, TransAnnot was 333, 284, and 18 times
  faster than comparable tools such as EnTAP, Trinotate, and eggNOG-mapper respectively.
  Availability and implementation TransAnnot is free to use, open sourced under GPLv3,
  and is implemented in C++ and Bash. Source code, documentation, and pre-compiled
  binaries are available at https://github.com/soedinglab/transannot. TransAnnot is
  also available via bioconda (https://anaconda.org/bioconda/transannot).
publication: '*Bioinformatics Advances*'
doi: 10.1093/bioadv/vbae152
links:
- name: URL
  url: https://academic.oup.com/bioinformaticsadvances/article/doi/10.1093/bioadv/vbae152/7831454
---
