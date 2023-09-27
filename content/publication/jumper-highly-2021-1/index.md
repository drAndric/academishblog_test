---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Highly Accurate Protein Structure Prediction with AlphaFold
subtitle: ''
summary: ''
authors:
- John Jumper
- Richard Evans
- Alexander Pritzel
- Tim Green
- Michael Figurnov
- Olaf Ronneberger
- Kathryn Tunyasuvunakool
- Russ Bates
- Augustin Žídek
- Anna Potapenko
- Alex Bridgland
- Clemens Meyer
- Simon A. A. Kohl
- Andrew J. Ballard
- Andrew Cowie
- Bernardino Romera-Paredes
- Stanislav Nikolov
- Rishub Jain
- Jonas Adler
- Trevor Back
- Stig Petersen
- David Reiman
- Ellen Clancy
- Michal Zielinski
- Martin Steinegger
- Michalina Pacholska
- Tamas Berghammer
- Sebastian Bodenstein
- David Silver
- Oriol Vinyals
- Andrew W. Senior
- Koray Kavukcuoglu
- Pushmeet Kohli
- Demis Hassabis
tags:
- Computational biophysics
- Machine learning
- Protein structure predictions
- Structural biology
categories: []
date: '2021-08-01'
lastmod: 2023-09-27T17:34:26-03:00
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
publishDate: '2023-09-27T20:34:25.969700Z'
publication_types:
- '2'
abstract: Proteins are essential to life, and understanding their structure can facilitate
  a mechanistic understanding of their function. Through an enormous experimental
  effort1–4, the structures of around 100,000 unique proteins have been determined5,
  but this represents a small fraction of the billions of known protein sequences6,7.
  Structural coverage is bottlenecked by the months to years of painstaking effort
  required to determine a single protein structure. Accurate computational approaches
  are needed to address this gap and to enable large-scale structural bioinformatics.
  Predicting the three-dimensional structure that a protein will adopt based solely
  on its amino acid sequence—the structure prediction component of the ‘protein folding
  problem’8—has been an important open research problem for more than 50~years9. Despite
  recent progress10–14, existing methods fall far~short of atomic accuracy, especially
  when no homologous structure is available. Here we provide the first computational
  method that can regularly predict protein structures with atomic accuracy even in
  cases in which no similar structure is known. We validated an entirely redesigned
  version of our neural network-based model, AlphaFold, in the challenging 14th Critical
  Assessment of protein Structure Prediction (CASP14)15, demonstrating accuracy competitive
  with experimental structures in a majority of cases and greatly outperforming other
  methods. Underpinning the latest version of AlphaFold is a novel machine learning
  approach that incorporates physical and biological knowledge about protein structure,
  leveraging multi-sequence alignments, into the design of the deep learning algorithm.
publication: '*Nature Publishing Group*'
doi: 10.1038/s41586-021-03819-2
---
