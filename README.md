
# ARCHIVED 

<red> The FReD Annotator is now part of the FReD R package - [forrtproject/FReD](https://github.com/forrtproject/FReD). This separate version will not be maintained. </red>

# fredAnnotator

<!-- badges: start -->
[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
<!-- badges: end -->

The goal of [FORRT's](https://forrt.org/) Replicability Annotator is to provide a simple way to annotate readings lists, and other reference lists, with information about replications and their outcomes. For this, we provide a Shiny web app, as well as a R package.

## Usage

You can use the Replicability Annotator [online](https://lukaswallrich.shinyapps.io/fredAnnotator/) or install the R package for local use.

``` r
devtools::install_github("forrtproject/fredAnnotator")
fredAnnotator::run_annotator()
```
