Gapminder Exercise Template
================
Becky Tang
2018-08-20

## Load packages

``` r
library(tidyverse)
```

## Load data

``` r
gap <- read_csv("https://bit.ly/gap_data_upd")
```

## Exercises

### Exercise 1

How many observations are in this dataset?

``` r
nrows <- nrow(gap)
```

There are 1704 observations in this dataset.

### Exercise 2

Visualize the relationship between GDP and life expectancy for countries
in Europe in 1952 using a scatter plot.

![](gapminder_files/figure-gfm/eu_52-1.png)<!-- -->

### Exercise 3

Add year 1967 in another color.

![](gapminder_files/figure-gfm/eu_52_67-1.png)<!-- -->
