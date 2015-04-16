---
layout: default
---

QuantGen Group
==================

Our group is interested in the analysis and prediction of complex traits and diseases using genetic (pedigrees, genome and other omics) and environmental information. Our research involves methods, software development, and applications in human health, plant and animal breeding. Our group has developed several R packages for the analysis of complex traits.

Projects
==================

**Genomic Analysis and Prediction of Complex Traits**. Development and evaluation of methods and software for analysis and prediction of complex traits using high-dimensional genomic data (e.g., SNPs, Gentoyping-by-sequencing, and other types of sequence data). Our research in this area has focused on the use of shrinkage and variable selection parameteric model as well as in the use of some semi-parameteric methods (e.g., RKHS). 

**Genomic x Environment** Development methods for integrating in a unified framework high-dimensional genomic and environmental data. We have develop methods that can model interactions between high dimensional marker panels and high-dimensional evironmental covariates. These methods were originally developed and tested with data from wheat trails (). We are currently extending some of these mehthos for analysis of complex human traits and diseases.

**Integration of data from multiple omic layers**. Development of models and software for integrating high dimensional multi-layer omic data. Our focus is on methods that can integrate whole-omic profiles and can model interactions between two or more high dimensional predictor sets (e.g., genome-by-methylome interactions). We are currently working on using these methods for prediction of breast cancer outcomes and in plant omic applications.

**Software development for analysis of big omic data**.

**Genomic Analysis of Obesity and Response to Excercise**.


Software
==================

**BGLR**.The Bayesian Generalized Linear Regression R package implements a variety of shrinkage and variable selection methods. The package can be used with whole-genome data (e.g., SNPs, gene expression or other omics), pedigrees and non-genetic covariates, including high-dimensional environmental data. [article](http://www.genetics.org/content/198/2/483.full.pdf+html) /      [download](http://cran.r-project.org/web/packages/BGLR/index.html)

**BGData**. Memory mapped matrices for R. [documentation](https://github.com/QuantGen/BGData/wiki) / [source](https://github.com/QuantGen/BGData/wiki)

**pedigreeR**. R functions related to pedigrees. [source](https://github.com/Rpedigree/pedigreeR)

**MTM**.Implements a Bayesian Multi-Trait Gaussian models with user defined-(co)variance structures. [documentation](https://www.dropbox.com/s/5tlr8hotsvcyam4/MTM%20documentation%20V2.docx?dl=0) / [source](https://www.dropbox.com/s/neyva73riidcfh5/MTM.R?dl=0)


People
==============

{% for member in site.team %}
{{ member.output }}
{% endfor %}
