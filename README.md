
<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Travis build status](https://travis-ci.org/llrs/BaseSet.svg?branch=master)](https://travis-ci.org/llrs/BaseSet) [![Coverage status](https://codecov.io/gh/llrs/BaseSet/branch/master/graph/badge.svg)](https://codecov.io/github/llrs/BaseSet?branch=master) [![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

BaseSet
=======

The goal of BaseSet is to facilitate working with sets

Installation
------------

You can install the released version of BaseSet from [Github](https://github.com/llrs/BaseSet) with:

``` r
remotes::install_github("llrs/BaseSet")
```

Example
-------

This is a basic example which shows you how to solve a common problem:

``` r
library("BaseSet")
set(c("a", "b", "c"))
#> An object of class "Set"
#> Slot "elements":
#>   a   b   c 
#> "a" "b" "c"
set(c("a", "b", "a"))
#> Error in validObject(.Object): invalid class "Set" object: All elements should be unique
```
