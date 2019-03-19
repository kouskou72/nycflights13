# NYCFlights R for data science
[![Travis Build
Status](https://travis-ci.org/tidyverse/ggplot2.svg?branch=master)](https://travis-ci.org/tidyverse/ggplot2)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/tidyverse/ggplot2?branch=master&svg=true)](https://ci.appveyor.com/project/tidyverse/ggplot2)
[![Coverage
Status](https://img.shields.io/codecov/c/github/tidyverse/ggplot2/master.svg)](https://codecov.io/github/tidyverse/ggplot2?branch=master)
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/ggplot2)](https://cran.r-project.org/package=ggplot2)

## Overview

Dans ce projet, j'ai travaillé sur le trafic aérien....

## Plan du projet

### Création de la BD SQL
Certains pb rencontrés sur les CSV : doublons, NA, données incohérentes... qui font en sorte que ni la PK ni la FK fonctionnent.

#### Création de flights_schema et flights_data SQL

# The easiest way to get ggplot2 is to install the whole tidyverse:
install.packages("tidyverse")

# Alternatively, install just ggplot2:
install.packages("ggplot2")

# Or the the development version from GitHub:
# install.packages("devtools")
devtools::install_github("tidyverse/ggplot2")
```

## Cheatsheet

<a href="https://github.com/rstudio/cheatsheets/blob/master/data-visualization-2.1.pdf"><img src="https://raw.githubusercontent.com/rstudio/cheatsheets/master/pngs/thumbnails/data-visualization-cheatsheet-thumbs.png" width="630" height="252"/></a>

## Usage

It’s hard to succinctly describe how ggplot2 works because it embodies a
deep philosophy of visualisation. However, in most cases you start with
`ggplot()`, supply a dataset and aesthetic mapping (with `aes()`). You
then add on layers (like `geom_point()` or `geom_histogram()`), scales
(like `scale_colour_brewer()`), faceting specifications (like
`facet_wrap()`) and coordinate systems (like `coord_flip()`).

``` r
library(ggplot2)

ggplot(mpg, aes(displ, hwy, colour = class)) + 
  geom_point()
```

![](man/figures/README-example-1.png)<!-- -->

## Lifecycle
