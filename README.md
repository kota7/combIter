
<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Build Status](https://travis-ci.org/kota7/combiter.svg?branch=master)](https://travis-ci.org/kota7/combiter) [![CRAN Status](http://www.r-pkg.org/badges/version/combiter)](http://www.r-pkg.org/badges/version/combiter) [![](http://cranlogs.r-pkg.org/badges/combiter)](http://cran.rstudio.com/web/packages/combiter/index.html)

combiter: Combinatorics Iterators for R
=======================================

This package provides iterators for combinations, permutations, subsets, and cartesian product, with which one can go through the elements without creating a huge set of all possible values.

Since `v1.0.2`, the iterator objects of the package inherit the `iter` class from [iterators](https://cran.r-project.org/web/packages/iterators/index.html) package. As a result, the objects are also compatible with [foreach](https://cran.r-project.org/web/packages/foreach/index.html) library.

Installation and import
-----------------------

Install from CRAN by:

``` r
install.packages("combiter")
```

Or install development version by:

``` r
devtools::install_github("kota7/combiter")
```

Use by

``` r
library(combiter)
```

Usage
-----

Please visit the [Documentation Page](https://kota7.github.io/combiter) for the package introduction.
