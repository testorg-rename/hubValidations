
<!-- README.md is generated from README.Rmd. Please edit that file -->

# hubValidations <img src="man/figures/logo.png" align="right" />

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![Codecov test
coverage](https://codecov.io/gh/Infectious-Disease-Modeling-Hubs/hubValidations/branch/main/graph/badge.svg)](https://app.codecov.io/gh/Infectious-Disease-Modeling-Hubs/hubValidations?branch=main)
[![R-CMD-check](https://github.com/Infectious-Disease-Modeling-Hubs/hubValidations/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/Infectious-Disease-Modeling-Hubs/hubValidations/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of hubValidations is to provide a testing framework for
performing hubverse hub validations.

## Installation

You can install the development version of hubValidations like so:

``` r
remotes::install_github("Infectious-Disease-Modeling-Hubs/hubValidations")
```

## Contributing new check functions

If submitting a new check function, please ensure you update
`inst/check_table.csv` with metadata about the check.
