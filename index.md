---
layout: default
---

QuantGen
========

Our group is interested in the analysis and prediction of complex traits and diseases using genetic (pedigrees, genome and other omics) and environmental information. Our research involves methods, software development, and applications in human health, plant and animal breeding. Our group has developed several R packages for the analysis of complex traits.


Projects
--------

### BGLR [Article](http://www.genetics.org/content/198/2/483.full.pdf+html)   [Download](http://cran.r-project.org/web/packages/BGLR/index.html)

The Bayesian Generalized Linear Regression R package implements a variety of shrinkage and variable selection methods. The package can be used with whole-genome data (e.g., SNPs, gene expression or other omics), pedigrees and non-genetic covariates, including high-dimensional environmental data.




### BGData

Memory mapped matrices for R.

- [Documentation](https://github.com/QuantGen/BGData/wiki)
- [Source Code](https://github.com/QuantGen/BGData/wiki)


### pedigreeR

R functions related to pedigrees

- [Source Code](https://github.com/Rpedigree/pedigreeR)


People
------

{% for member in site.team %}
{{ member.output }}
{% endfor %}
