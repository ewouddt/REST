
<!-- README.md is generated from README.Rmd. Please edit that file -->
REST - Quickly making R Commander Plug-ins
==========================================

`REST` (**R**cmdr **E**asy **S**cript **T**emplates) is a tool for R Commander Plug-In development.

This package is by no means as flexible or powerful as `shiny`, but it does provide you a quick, easy and no-nonsense way to create a **R Commander plug-in** for your own analysis or R package while not having to bother about any `tlctk` syntax.

For an detailed guide on how to use `REST`, please check the vignette of the package.

Installing REST
---------------

**CRAN Release Version**

``` r
install.packages("REST")
```

**Development Release** (GitHub or R-Forge)

``` r
install.packages("REST",repos="http://R-Forge.R-project.org")
```

or

``` r
setRepositories(ind=c(1:5))
install.packages("devtools") # If not yet installed on your R Version
devtools::install_github("hadley/devtools") # Only run this if your currently installed 
                                            # devtools version is <= 1.12 (recursive dependencies bug)

devtools::install_github("ewouddt/REST")
```

Info & Links
------------

-   *Detailed Guide* (See /vignettes/RESTguide.pdf).
-   *R-Forge Project Page* ([R-Forge](https://r-forge.r-project.org/R/?group_id=2045)).
