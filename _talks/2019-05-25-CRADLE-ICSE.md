---
title: "CRADLE: Cross-Backend Validation to Detect and Localize Bugs in Deep Learning Libraries"
collection: talks
type: "Conference proceedings talk"
permalink: /talks/2019-05-25-CRADLE-ICSE
venue: "41st ACM/IEEE International Conference on Software Engineering"
date: 2019-05-25
location: "Montreal, QC, Canada"
---

We propose CRADLE, a new approach that focuses on finding and localizing bugs in DL software libraries. CRADLE (1) performs cross-implementation inconsistency checking to detect bugs in DL libraries, and (2) leverages anomaly propagation tracking and analysis to localize faulty functions in DL libraries that cause the bugs. We evaluate CRADLE on three libraries (TensorFlow, CNTK, and Theano), 11 datasets (including ImageNet, MNIST, and KGS Go game), and 30 pre-trained models. CRADLE detects 12 bugs and 104 unique inconsistencies, and highlights functions relevant to the causes of inconsistencies for all 104 unique inconsistencies.

[Slides](https://hvpham.github.io/files/CRADLE-slides.pdf)