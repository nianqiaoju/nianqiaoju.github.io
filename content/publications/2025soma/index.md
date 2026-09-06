---
title: "SOMA: A Novel Sampler for Bayesian Inference from Privatized Data"

authors:
  - Yifei Xiong
  - me

date: 2025-05-01
publishDate: 2023-12-20

# Publication type (CSL standard).
publication_types: ['article']

publication: Arxiv preprint
publication_short: ""

abstract: "Making valid statistical inferences from privatized data is a key challenge in modern analysis. In Bayesian settings, data augmentation MCMC (DAMCMC) methods impute unobserved confidential data given noisy privatized summaries, enabling principled uncertainty quantification. However, standard DAMCMC often suffers from slow mixing due to component-wise Metropolis-within-Gibbs updates. We propose the Single-Offer-Multiple-Attempts (SOMA) sampler. This novel algorithm improves acceptance rates by generating a single proposal and simultaneously evaluating its suitability to replace all components. By sharing proposals across components, SOMA rejects fewer proposal points. We prove lower bounds on SOMA's acceptance probability and establish convergence rates in the two-component case. Experiments on synthetic and real census data with linear regression and other models confirm SOMA's efficiency gains."

summary: ""

tags:
  - Gibbs sampler
  - MCMC
  - data augmentation
  - differential privacy

featured: true

hugoblox:
  ids:
    arxiv: 2505.00635


# Preserve the URL used by the previous Wowchemy site.
aliases:
  - /publication/soma/
---
