# Data Poisoning for Imbalanced Classification

### Code Repository for paper (Coming Soon):
##### "Towards Effective Data Poisoning for Imbalanced Classification", Adversarial Machine Learning Workshop (AdvML Frontiers 2023) at International Conference on Machine Learning (ICML) 2023. 

## Abstract

Targeted Clean-label Data Poisoning Attacks (TCPDA) aim to manipulate training samples in a label-consistent manner to gain malicious control over targeted samples' output during deployment. A prominent class of TCDPA methods, gradient-matching based data-poisoning methods, utilize a small subset of training class samples to match the poisoned gradient of a target sample. However, their effectiveness is limited when attacking imbalanced datasets because of gradient mis-match due to training time data balancing techniques like Re-weighting and Re-sampling. In this paper, we propose two modifications that eliminate this gradient-mismatch and thereby enhance the efficacy of gradient-matching-based TCDPA on imbalanced datasets. Our methods achieve notable improvements of up to 32% (Re-sampling) and 51% (Re-weighting) in terms of Attack Effect Success Rate on MNIST and CIFAR10.
