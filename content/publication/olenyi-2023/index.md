---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'LambdaPP: Fast and accessible protein‐specific phenotype predictions'
subtitle: ''
summary: ''
authors:
- Tobias Olenyi
- Céline Marquet
- Michael Heinzinger
- Benjamin Kröger
- Tiha Nikolova
- Michael Bernhofer
- Philip Sändig
- Konstantin Schütze
- Maria Littmann
- Milot Mirdita
- Martin Steinegger
- Christian Dallago
- Burkhard Rost
tags:
- artificial intelligence
- protein annotation
- protein function prediction
- protein language models
- protein structure prediction
- web server
categories: []
date: '2023-01-01'
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
publishDate: '2023-12-16T10:48:02.912172Z'
publication_types:
- '2'
abstract: The availability of accurate and fast artificial intelligence (AI) solutions
  predicting aspects of proteins are revolutionizing experimental and computational
  molecular biology. The webserver LambdaPP aspires to supersede PredictProtein, the
  first internet server making AI protein predictions available in 1992. Given a protein
  sequence as input, LambdaPP provides easily accessible visualizations of protein
  3D structure, along with predictions at the protein level (GeneOntology, subcellular
  location), and the residue level (binding to metal ions, small molecules, and nucleotides;
  conservation; intrinsic disorder; secondary structure; alpha‐helical and beta‐barrel
  transmembrane segments; signal‐peptides; variant effect) in seconds. The structure
  prediction provided by LambdaPP —leveraging ColabFold and computed in minutes —is
  based on MMseqs2 multiple sequence alignments. All other feature prediction methods
  are based on the pLM ProtT5 . Queried by a protein sequence, LambdaPP computes protein
  and residue predictions almost instantly for various phenotypes, including 3D structure
  and aspects of protein function. LambdaPP is freely available for everyone to use
  under embed.predictprotein.org , the interactive results for the case study can
  be found under https://embed.predictprotein.org/o/Q9NZC2 . The frontend of LambdaPP
  can be found on GitHub ( github.com/sacdallago/embed.predictprotein.org ), and can
  be freely used and distributed under the academic free use license (AFL‐2). For
  high‐throughput applications, all methods can be executed locally via the bio‐embeddings
  ( bioembeddings.com ) python package, or docker image at ghcr.io/bioembeddings/bio_embeddings
  , which also includes the backend of LambdaPP.
publication: '*Protein Science*'
doi: 10.1002/pro.4524
links:
- name: URL
  url: https://doi.org/10.1002/pro.4524 https://onlinelibrary.wiley.com/doi/10.1002/pro.4524
---
