---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Building High-Level Features Using Large Scale Unsupervised Learning
subtitle: ''
summary: ''
authors:
- Quoc V. Le
- Marc'Aurelio Ranzato
- Rajat Monga
- Matthieu Devin
- Kai Chen
- Greg S. Corrado
- Jeff Dean
- Andrew Y. Ng
tags:
- ⛔ No DOI found
- Computer Science - Machine Learning
categories: []
date: '2012-07-12'
lastmod: 2023-09-27T17:46:55-03:00
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
publishDate: '2023-09-27T20:46:55.317867Z'
publication_types:
- '3'
abstract: We consider the problem of building high-level, class-specific feature detectors
  from only unlabeled data. For example, is it possible to learn a face detector using
  only unlabeled images? To answer this, we train a 9-layered locally connected sparse
  autoencoder with pooling and local contrast normalization on a large dataset of
  images (the model has 1 billion connections, the dataset has 10 million 200x200
  pixel images downloaded from the Internet). We train this network using model parallelism
  and asynchronous SGD on a cluster with 1,000 machines (16,000 cores) for three days.
  Contrary to what appears to be a widely-held intuition, our experimental results
  reveal that it is possible to train a face detector without having to label images
  as containing a face or not. Control experiments show that this feature detector
  is robust not only to translation but also to scaling and out-of-plane rotation.
  We also find that the same network is sensitive to other high-level concepts such
  as cat faces and human bodies. Starting with these learned features, we trained
  our network to obtain 15.8% accuracy in recognizing 20,000 object categories from
  ImageNet, a leap of 70% relative improvement over the previous state-of-the-art.
publication: ''
links:
- name: URL
  url: http://arxiv.org/abs/1112.6209
---
