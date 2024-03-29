---
author: Gabriel Nakamura, Arthur Rodriges, Andre Luza, Vanderlei Debastiani, Renan Maestri, Leandro Duarte
categories:
- R
- package
date: "2022-07-05"
draft: false
excerpt: ""
layout: single
links:
- icon: door-open
  icon_pack: fas
  name: website
  url: gabrielnakamura.github.io/herodotools/
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/GabrielNakamura/Herodotools
subtitle:  Analysis for historical biogeography
tags:
- hugo-site
title: Herodotools
---

# Herodotools

<img src="man/figures/logo_herodotools.png" alt="package logo with a map and a phylogeny inside" width="250px" align="right"/>

# Herodotools

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://choosealicense.com/licenses/mit/)

[![DOI](https://zenodo.org/badge/363983380.svg)](https://zenodo.org/badge/latestdoi/363983380)

# General overview

`{Herodotools}` is an R package that allows to perform analysis to investigate the effects of historical processes, specifically diversification
    and historical dispersal, in determine the biodiversity structure of assemblages and biogeographical regions. This is achieved by integrating 
    tools of macroevolutionary dynamics (e.g. ancestral area reconstruction, trait reconstruction) with metrics commonly used in community phylogenetics,
    and also by providing new metrics that integrate the macroevolutionary dynamics in assemblage or biogeographical scales. Some of the functions
    presented in `{Herodotools}` package has been used in previous studies to understand, for example, imprints of historical processes in present
    day patterns of diversity, [macroecological patterns](https://academic.oup.com/biolinnean/article-abstract/134/1/57/6297962) and the interplay effects of [ecological variation and macroevolutionary dynamics](https://onlinelibrary.wiley.com/doi/full/10.1002/ece3.8476#:~:text=We%20found%20that%20environmentally%20heterogeneous,diet%20transitions%20in%20sigmodontine%20rodents.)
    
In general, `Herodotools` was designed to work as a unified platform of analysis of historical biogeography by integrating methods from Macroecology, Macroevolution and Community Phylogenetics.

# Download 

To install the development version of this package the user must type:

```{.r}
# install.packages("devtools")
devtools::install_github("GabrielNakamura/Herodotools", ref = "main")
```

# Example

For more details and examples please visit [Herodotools web page](https://gabrielnakamura.github.io/Herodotools/)

# Authors

Gabriel Nakamura, Arthur Rodrigues, André Luza, Renan Maestri, Vanderlei Debastiani and Leandro Duarte


