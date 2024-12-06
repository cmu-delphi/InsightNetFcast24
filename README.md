
<!-- README.md is generated from README.Rmd. Please edit that file -->

# InsightNetFcast24

<!-- badges: start -->
<!-- badges: end -->

The goal of `{InsightNetFcast24}` is to allow attendees of the workshop
to install all necessary packages at once.

## Installation

You should install `{InsightNetFcast24}` like so:

``` r
install.packages("pak")
pak::pkg_install("cmu-delphi/InsightNetFcast24", dependencies = TRUE)
```

## Verifying set up

Installing this package should install the correct versions for all the
packages needed to build the materials. This is actually a bit more than
you need to *run* the materials.

There’s only one function, and it just checks that all the dependencies
are installed.

``` r
library(InsightNetFcast24)
verify_setup()
#> ✔ You should be good to go!
```