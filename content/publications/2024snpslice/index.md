---
title: "SNP-Slice: A Bayesian nonparametric framework to resolve SNP haplotypes in mixed infections"

authors:
  - me
  - Jiawei Liu
  - Qixin He

date: 2024-06-14
publishDate: 2023-07-30

# Publication type (CSL standard).
publication_types: ['article-journal']

publication: "Bioinformatics"
publication_short: ""

abstract: "Multi-strain infection is a common yet under-investigated phenomenon of many pathogens. Currently,biologists analyzing SNP information have to discard mixed infection samples,because existing downstream analyses require monogenomic infection inputs.Such a protocol impedes our understanding of the real genetic diversity, co-infection patterns,and genomic relatedness of pathogens.A reliable tool to learn and resolve the SNP haplotypes from polygenomic data is an urgent need in molecular epidemiology.In this work,we develop a slice sampling Markov Chain Monte Carlo algorithm,named SNP-Slice,to learn not only the SNP haplotypes of all strains in the populations but also which strains infect each host. Our method reconstructs SNP haplotypes and allele frequencies accurately without reference panels and outperforms the state of art methods at estimating the multiplicity of infections,allele frequencies,and heterozygosity. We illustrate the performance ofS NP-Slice on empirical malaria and HIV datasets."

summary: ""

tags:
  - computational biology
  - MCMC
  - Bayesian inference
  - Gibbs sampler

featured: true

links:
  - type: pdf
    url: https://academic.oup.com/bioinformatics/article/40/6/btae344/7695237
  - type: code
    url: https://github.com/nianqiaoju/snp-slice

# Preserve the URL used by the previous Wowchemy site.
aliases:
  - /publication/snpslice/
---
