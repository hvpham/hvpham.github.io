---
title: "Problems and opportunities in training deep learning software systems: an analysis of variance"
collection: talks
type: "Conference proceedings talk"
permalink: /talks/2019-09-23-Variance-ASE
venue: "35th IEEE/ACM conference on Automated Software Engineering"
date: 2019-09-23
location: "Virtual Arts Centre Melbourne, Australia"
---

Deep learning (DL) training algorithms utilize nondeterminism to improve models' accuracy and training efficiency. Hence, multiple identical training runs (e.g., identical training data, algorithm, and network) produce different models with different accuracies and training times. In addition to these algorithmic factors, DL libraries (e.g., TensorFlow and cuDNN) introduce additional variance (referred to as implementation-level variance) due to parallelism, optimization, and floating-point computation.

This work is the first to study the variance of DL systems and the awareness of this variance among researchers and practitioners. Our experiments on three datasets with six popular networks show large overall accuracy differences among identical training runs. Even after excluding weak models, the accuracy difference is 10.8%. In addition, implementation-level factors alone cause the accuracy difference across identical training runs to be up to 2.9%, the per-class accuracy difference to be up to 52.4%, and the training time difference to be up to 145.3%.

[Slides](https://hvpham.github.io/files/Variance-slides.pdf)