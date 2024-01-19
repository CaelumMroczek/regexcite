
<!-- README.md is generated from README.Rmd. Please edit that file -->

# regexcite

<!-- badges: start -->
<!-- badges: end -->

The goal of regexcite is to make regular expressions more exciting!

## Installation

You can install the development version of regexcite from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("cmroczek97/regexcite")
```

## Example

This is a basic example to demonstrate the use of the :

``` r
library(regexcite)

x <- "a,b,c,d"

str_split_one(x, ",")
#> [1] "a" "b" "c" "d"
```
