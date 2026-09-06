---
title: "Simulation-based Bayesian inference from privacy-protected data"

authors:
  - Yifei Xiong
  - me
  - Sanguo Zhang

date: 2025-03-29
publishDate: 2023-10-20

# Publication type (CSL standard).
publication_types: ['article-journal']

publication: "Transactions of Machine Learning Research"
publication_short: "TMLR"

abstract: "Many modern statistical analysis and machine learning applications require training models on sensitive user data. Differential privacy provides a formal guarantee that individual-level information about users does not leak. In this framework, randomized algorithms inject calibrated noise into the confidential data, resulting in privacy-protected datasets or queries. However, restricting access to only the privatized data during statistical analysis makes it computationally challenging to perform valid inferences on parameters underlying the confidential data. In this work, we propose simulation-based inference methods from privacy-protected datasets. Specifically, we use neural conditional density estimators as a flexible family of distributions to approximate the posterior distribution of model parameters given the observed private query results. We illustrate our methods on discrete time-series data under an infectious disease model and on ordinary linear regression models. Illustrating the privacy-utility trade-off, our experiments and analysis demonstrate the necessity and feasibility of designing valid statistical inference procedures to correct for biases introduced by the privacy-protection mechanisms."

summary: ""

tags:
  - differential privacy
  - simulation-based inference

featured: false

hugoblox:
  ids:
    arxiv: 2310.12781

links:
  - type: code
    url: https://github.com/Yifei-Xiong/Simulation-based-Bayesian-Inference-from-Privacy-Protected-Data

# Preserve the URL used by the previous Wowchemy site.
aliases:
  - /publication/neuraldensity/
---
