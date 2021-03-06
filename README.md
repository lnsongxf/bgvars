
<!-- README.md is generated from README.Rmd. Please edit that file -->
bgvars
======

[![CRAN status](https://www.r-pkg.org/badges/version/bgvars)](https://cran.r-project.org/package=bgvars) [![Travis build status](https://travis-ci.org/franzmohr/bgvars.svg?branch=master)](https://travis-ci.org/franzmohr/bgvars)

Overview
--------

The `bgvars` package provides functions for the specification, estimation and evaluation of Bayesian global autoregressive (GVAR) models. Global vector autoregressive (GVAR) models are convenient tools to model the world economy. They were originally proposed by Pesaran et al. (2004) and further developed by Dees et al. (2007) to study the international transmission of shocks. Since then they have been applied to a range of macroeconomic topics. Chudik and Pesaran (2016) provide an extensive survey of the latest developments in GVAR modelling.

Installation
------------

### Development version

``` r
# install.packages("devtools")
devtools::install_github("franzmohr/bgvars")
```

Usage
-----

A typical analysis consists of four steps:

-   Data preparation
-   Country model specification
-   Estimating and solving the GVAR model
-   Impulse response analysis

### Data preparation

The `bgvars` packages comes with the updated GVAR database of Mohaddes and Raissi (2018), which contains economic time series for 33 countries and 3 commodities from 1979Q2 to 2016Q4.[1]

### Model specification

### Estimation

### Solving the GVAR model

### Impulse response analysis

References
----------

[1] The paper and dataset can be downloaded from <http://www.econ.cam.ac.uk/people-files/faculty/km418/research.html#gvar>.
