
<!-- README.md is generated from README.Rmd. Please edit that file -->

# DNA Methylation Arrays Processing And Quality-Control

<!-- badges: start -->

[![Lifecycle:
questioning](https://img.shields.io/badge/lifecycle-questioning-orange.svg)]()
[![GitHub
tag](https://img.shields.io/github/tag/umr1283/dmapaq.svg?label=latest%20tag&include_prereleases)](https://github.com/umr1283/dmapaq)
[![R build
status](https://github.com/umr1283/dmapaq/workflows/R-CMD-check/badge.svg)](https://github.com/umr1283/dmapaq/actions)
<!-- badges: end -->

## Installation

``` r
# Install dmapaq from CRAN:
install.packages("dmapaq")

# Or the the development version from GitHub:
# install.packages("remotes")
remotes::install_github("umr1283/dmapaq")
```

## Overview

  - `read_idats()` allows to efficiently import idats files mostly using
    [minfi](https://bioconductor.org/packages/minfi/) functions.
  - `qc_idats()` allows to compute quality-control of methylation array
    from Illumina using a [rmarkdown
    template](inst/rmarkdown/templates/qc_idats/skeleton/skeleton.Rmd).

-----

## Getting help

If you encounter a clear bug, please file a minimal reproducible example
on [github](https://github.com/umr1283/dgapaq/issues).  
For questions and other discussion, please contact the package
maintainer.

## Code of Conduct

Please note that the `dmapaq` project is released with a [Contributor
Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
