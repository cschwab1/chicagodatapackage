# ChicagoPackage

<!-- badges: start -->
<!-- badges: end -->

My name is Clyde Schwab, and I'm (currently) an undergraduate at the University of Chicago studying geography and environmental and urban studies. The goal of this package is multifaceted — to provide a starting point for those interested in learning geocomputation with R using real Chicago data or those interested in working on a Chicago-specific issue, but also to begin building a larger collection of civic data for academic and amateur, journalist and researcher, non-profit and concerned citizen alike. 

I've tried to provide a rough skeleton with some datasets that seemed important. While much of it has already been processed (the code for doing so has been provided in devplayground.R), I have also attempted to provide some basic steps for including further processed code. Cleaned datasets are available in /data, and I've included the unprocessed data in /data-raw. The data was primarily collected from the Chicago data portal (https://data.cityofchicago.org/), but also contains datasets from the CDC and Cook County. Additional documentation is available in /R. 

More immediately, there are some basic issues I want to resolve — first, finishing a few vignettes as a tutorial/intro to wrangling Chicago data, and a larger overview on good sources of data for the city. I also want to use RShiny to create an interactive way of viewing this and more data. I also am working on a function to aggregate data on the census level more effeciently, using the CPS Tier and SVI data as an example. 

I intend for this project to be ongoing, and am excited to see how it grows moving forward. Possible directions include separate, smaller datasets containing data surrounding things like criminal justice (think police misconduct records, shotspotter data, or prisoner reentry), environmental issues (lead and brownfields, raster data on polution), or education. I'm also especially interested in including further time sequenced data, which would be necessary for any substantive analysis, but the recent creation of the data portal poses problems here. I am now in the process of collecting interesting datasets from UChicago's academic establishment, and interested in expanding this to Chicago's other amazing institutions. 

## Installation

You can install the released version of ChicagoPackage from [CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("ChicagoPackage")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(ChicagoPackage)
## basic example code
```

