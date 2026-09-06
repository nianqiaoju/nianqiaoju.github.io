---
title: "Data Augmentation MCMC for Bayesian Inference from Privatized Data"

authors:
  - me
  - Jordan A. Awan
  - Ruobin Gong
  - Vinayak A. Rao

date: 2022-06-01
publishDate: 2022-06-01

# Publication type (CSL standard).
publication_types: ['paper-conference']

publication: NeurIPS 2022
publication_short: ""

abstract: "Differentially private mechanisms protect privacy by introducing additional randomness into the data. Restricting access to only the privatized data makes it challenging to perform valid statistical inference on parameters underlying the confidential data. Specifically, the likelihood function of the privatized data requires integrating over the large space of confidential databases and is typically intractable. For Bayesian analysis, this results in a posterior distribution that is doubly intractable, rendering traditional MCMC techniques inapplicable. We propose an MCMC framework to perform Bayesian inference from the privatized data, which is applicable to a wide range of statistical models and privacy mechanisms. Our MCMC algorithm augments the model parameters with the unobserved confidential data, and alternately updates each one conditional on the other. For the potentially challenging step of updating the confidential data, we propose a generic approach that exploits the privacy guarantee of the mechanism to ensure efficiency. In particular, we give results on the computational complexity, acceptance rate, and mixing properties of our MCMC. We illustrate the efficacy and applicability of our methods on a naïve-Bayes log-linear model as well as on a linear regression model."

summary: ""

tags:
  - MCMC
  - differential privacy
  - data augmentation

featured: true

hugoblox:
  ids:
    arxiv: 2206.00710

links:
  - type: code
    url: https://github.com/nianqiaoju/dataaugmentation-mcmc-differentialprivacy

# Preserve the URL used by the previous Wowchemy site.
aliases:
  - /publication/dpneurips/
---
