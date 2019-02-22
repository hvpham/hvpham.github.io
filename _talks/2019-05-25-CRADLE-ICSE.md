---
title: "CRADLE: Cross-Backend Validation to Detect and Localize Bugs in Deep Learning Libraries"
collection: talks
type: "Conference proceedings talk"
permalink: /talks/2019-05-25-CRADLE-ICSE
venue: "41st ACM/IEEE International Conference on Software Engineering"
date: 2019-05-25
location: "Montreal, QC, Canada"
---

## Abstract
Deep learning (DL) systems are widely used in domains including aircraft collision avoidance systems, Alzheimer’s
disease diagnosis, and autonomous driving cars. Despite the requirement for high reliability, DL systems are difficult to test.

Existing DL testing work focuses on testing the DL models, not the implementations (e.g., DL software libraries) of the models. One key challenge of testing DL libraries is the difficulty of knowing the expected output of DL libraries given an input instance. Fortunately, there are multiple implementations of the same DL algorithms in different DL libraries.

Thus, we propose CRADLE, a new approach that focuses on finding and localizing bugs in DL software libraries. CRADLE (1) performs cross-implementation inconsistency checking to detect bugs in DL libraries, and (2) leverages anomaly propagation tracking and analysis to localize faulty functions in DL libraries that cause the bugs. We evaluate CRADLE on three libraries (TensorFlow, CNTK, and Theano), 11 datasets (including ImageNet, MNIST, and KGS Go game), and 30 pre-trained models. CRADLE detects 12 bugs and 104 unique inconsistencies, and highlights functions relevant to the causes of inconsistencies for all 104 unique inconsistencies. about the number 1. The number 2 is left for future work.

[Download paper here](https://cs.uwaterloo.ca/~hvpham/CRADLE-icse19.pdf)