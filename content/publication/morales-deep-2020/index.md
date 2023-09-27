---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Deep Learning for Gravitational-Wave Data Analysis: A Resampling White-Box
  Approach'
subtitle: ''
summary: ''
authors:
- Manuel D. Morales
- Javier M. Antelis
- Claudia Moreno
- Alexander I. Nesterov
tags:
- ⛔ No DOI found
- Astrophysics - Instrumentation and Methods for Astrophysics
- Computer Science - Machine Learning
- General Relativity and Quantum Cosmology
- Physics - Data Analysis
- Statistics and Probability
categories: []
date: '2020-09-08'
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
publishDate: '2023-09-27T20:46:55.734507Z'
publication_types:
- '3'
abstract: In this work, we apply Convolutional Neural Networks (CNNs) to detect gravitational
  wave (GW) signals of compact binary coalescences, using single-interferometer data
  from LIGO detectors. As novel contribution, we adopted a resampling white-box approach
  to advance towards a statistical understanding of uncertainties intrinsic to CNNs
  in GW data analysis. Resampling is performed by repeated $k$-fold cross-validation
  experiments, and for a white-box approach, behavior of CNNs is mathematically described
  in detail. Through a Morlet wavelet transform, strain time series are converted
  to time-frequency images, which in turn are reduced before generating input datasets.
  Moreover, to reproduce more realistic experimental conditions, we worked only with
  data of non-Gaussian noise and hardware injections, removing freedom to set signal-to-noise
  ratio (SNR) values in GW templates by hand. After hyperparameter adjustments, we
  found that resampling smooths stochasticity of mini-batch stochastic gradient descend
  by reducing mean accuracy perturbations in a factor of $3.6$. CNNs were quite precise
  to detect noise but not sensitive enough to recall GW signals, meaning that CNNs
  are better for noise reduction than generation of GW triggers. However, applying
  a post-analysis, we found that for GW signals of SNR $ geq 21.80$ with H1 data and
  SNR $ geq 26.80$ with L1 data, CNNs could remain as tentative alternatives for detecting
  GW signals. Besides, with receiving operating characteristic curves we found that
  CNNs show much better performances than those of Naive Bayes and Support Vector
  Machines models and, with a significance level of $5%$, we estimated that predictions
  of CNNs are significant different from those of a random classifier. Finally, we
  elucidated that performance of CNNs is highly class dependent because of the distribution
  of probabilistic scores outputted by the softmax layer.
publication: ''
links:
- name: URL
  url: http://arxiv.org/abs/2009.04088
---
