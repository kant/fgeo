
<!-- README.md is generated from README.Rmd. Please edit that file -->
fgeo: Analyze forest dynamics <img src="inst/figures/logo.png" align="right" />
===============================================================================

[![Travis build status](https://travis-ci.org/forestgeo/fgeo.svg?branch=master)](https://travis-ci.org/forestgeo/fgeo) [![Coverage status](https://codecov.io/gh/forestgeo/fgeo/branch/master/graph/badge.svg)](https://codecov.io/github/forestgeo/fgeo?branch=master) [![CRAN status](http://www.r-pkg.org/badges/version/fgeo)](https://cran.r-project.org/package=fgeo)

Overview
--------

**fgeo** installs and loads multiple R packages of [ForestGEO](http://www.forestgeo.si.edu/) in a single step. Together, all packages in **fgeo** provide a wide renge of tools to analyse forest dynamics.

[See all packages](https://forestgeo.github.io/fgeo/reference/index.html)

Installation
------------

    # To install from a private repo, see auth_token at https://goo.gl/re1LFe
    # install.packages("remotes")
    remotes::install_github("forestgeo/fgeo")

Usage
-----

`library(fgeo)` will load the core **fgeo** packages.

``` r
library(fgeo)
#> -- Attaching packages ---------------------------------------------- fgeo 0.0.0.9000 --
#> v forestr    0.0.0.9000     v bciex      0.0.0.9000
#> v map        0.0.0.9007     v demography 0.0.0.9000
#> 
```

You can see conflicts with other packages with `fgeo_conflicts()`.

``` r
fgeo_conflicts()
```
