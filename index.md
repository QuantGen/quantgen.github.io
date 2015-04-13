---
layout: default
---

QuantGen
========

Our group is interested in the analysis and prediction of complex traits and diseases using genetic (pedigrees, genome and other omics) and environmental information. Our research involves methods, software development, and applications in human health, plant and animal breeding. Our group has developed several R packages for the analysis of complex traits.


Projects
--------

* [BGData](https://github.com/QuantGen/BGData): memory mapped matrices for R
* [pedigreeR](https://github.com/Rpedigree/pedigreeR): R functions related to pedigrees


People
------

{% for member in site.team %}
{{ member.output }}
{% endfor %}
