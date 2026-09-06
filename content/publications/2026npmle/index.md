---
title: "Statistical Properties of Nonparametric MLE under Laplace Noise"

authors:
  - Yifei Xiong
  - me
  - Vinayak Rao

date: 2026-08-26
publishDate: 2026-08-26

# Publication type (CSL standard).
publication_types: ['article']

publication: Arxiv preprint
publication_short: ""

abstract: "Local differential privacy (LDP) protects individuals in a dataset by perturbing each measurement before release. For real-valued data, a widely used mechanism is additive Laplace noise. We study the problem of estimating the distribution of the latent confidential data from the privatized observations via the nonparametric maximum likelihood estimator (NPMLE) under an i.i.d. sampling model. We first show that under the Laplace convolution model, the NPMLE admits a finite-dimensional reformulation in which the support is restricted to the observation set. This reduces the original infinite-dimensional optimization over all mixing distributions to an $n$-dimensional convex optimization over mixture weights, where $n$ is the sample size. We then study the statistical convergence of the NPMLE under the 1-Wasserstein distance, and explicitly connect its convergence rate with the privacy noise scale. Allowing the privacy noise level to change with the sample size, our analysis shows that the NPMLE remains consistent when the Laplace noise grows at a rate slower than $n^{3/16}$. Conversely, when the Laplace noise is of the order $\\sqrt{n}$ or larger, no estimator can achieve uniformly consistent recovery of the latent distribution."

summary: ""

tags:
  - differential privacy
  - nonparametric inference

featured: false

hugoblox:
  ids:
    arxiv: 2608.25997
---
