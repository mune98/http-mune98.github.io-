---
title: "Sparsity Aware Orthogonal Initialization of Deep Neural Networks."
collection: publications
category: journal
permalink: https://doi.org/10.1109/ACCESS.2023.3295344
excerpt: 'Deep neural networks have achieved impressive pattern recognition and generative abilities on complex tasks by developing larger and deeper models, which are increasingly costly to train and implement. There is in tandem interest to develop sparse versions of these powerful models by post-processing with weight pruning or dynamic sparse training. However, these processes require expensive train-prune-finetune cycles and compromise the trainability of very deep network configurations. We introduce sparsity-aware orthogonal initialization (SAO), a method to initialize sparse but maximally connected neural networks with orthogonal weights. SAO constructs a sparse network topology leveraging Ramanujan expander graphs to assure connectivity and assigns orthogonal weights to attain approximate dynamical isometry. Sparsity in SAO networks is tunable prior to model training. We compared SAO to fully-connected neural networks and demonstrated that SAO networks outperform magnitude pruning in very deep and sparse networks up to a thousand layers with fewer computations and training iterations. Convolutional neural networks are SAO networks with special constraints, while kernel pruning may be interpreted as tuning the SAO sparsity level. Within SAO framework, kernels may be pruned prior to model training based on a desired compression factor rather than post-training based on parameter-dependent heuristics. SAO is well-suited for applications with tight energy and computation budgets such as edge computing tasks, because it achieves sparse, trainable neural network models with fewer learnable parameters without requiring special layers, additional training, scaling, or regularization. The advantages of SAO networks are attributed to both its sparse but maximally connected topology and orthogonal weight initialization.'
date: 2023-07-13
venue: 'IEEE Access'
citation: 'Esguerra, K. (2023). &quot;Sparsity Aware Orthogonal Initialization of Deep Neural Networks.&quot; IEEE Access, vol. 11, pp. 74165-74181.'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.