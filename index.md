
# Giotto Suite

\[under construction\] Giotto Suite is the new and updated version of
Giotto.

<img src="./inst/images/general_figs/Giotto_to_suite.png" style="width:80.0%" />

<br>

### latest update:

    ## [1] "2021-09-24"

<br>

## Installation:

You can install Giotto Suite on any platform in 2 easy steps:

#### Step 1: install Giotto Suite

``` r
library(remotes)
remotes::install_github("RubD/Giotto@suite") 
```

#### Step 2: install the Giotto python environment

The python environment only needs to be installed once.

``` r
library(Giotto)
installGiottoEnvironment()
```

This command only needs to be run once and then Giotto will
automatically detect the environment in the future.

For more information:

-   See
    [Installation](https://giottosuite.com/articles/temp_construction.html)
    for alternative (manual) installation options.  
-   See [Giotto
    Environment](https://giottosuite.com/articles/temp_construction.html)
    to learn more about the Giotto environment.  
-   See [FAQ](https://giottosuite.com/articles/faq.html) for
    troubleshooting.

<br>

## Summary:

<!-- badges: start -->
<!-- badges: end -->

**Giotto Suite** is a suite of software tools, including data structures
and methods, for the comprehensive analysis and visualization of spatial
expression data. It was developed to extend and improve our previous R
package Giotto. This will ensure that our spatial analysis solutions
remain compatible with all current and future developed spatial
technologies and platforms. It will also aid in the further integration
with other external analysis pipelines and tools.

The most important changes and additions are:

-   support for multi-modal datasets (e.g. RNA + Protein)
-   support for subcellular data
    -   efficient representations for image information (e.g. nucleus,
        membrane, …)  
    -   individual transcript locations
    -   subcellular analyses
-   image processing tools
    -   registration  
    -   segmentation
    -   integration
    -   efficient visualization
-   Joint analysis: combining, batch correcting and analyzing multiple
    spatial datasets  
-   Large file management:
    -   DelayedArray  
    -   terra

<br>

## References

-   [Dries, R., Zhu, Q. et al. Giotto, a toolbox for integrative
    analysis and visualization of spatial expression data. Genome
    Biology
    (2021).](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02286-2)
      
-   \[Coming soon\] Spatial review.