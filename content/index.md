---
title: "Open and Reproducible Research with R at useR!2017"
author: François Michonneau
date: 2017-07-04
type: index
weight: 0
---

> Tutorial taught by Mine Cetinkaya-Rundel and Colin Rundel
>
> Assembled by François Michonneau and Hilmar Lapp,
> using material from the [Reproducible Research Curriculum](http://www.datacarpentry.org/rr-workshop)

We are excited to announce that our [workshop proposal](proposal/) "Open and
Reproducible Research with R" has been accepted as a tutorial
for [useR!2017](http://www.user2017.brussels/), Brussels. The tutorial session
will take place on July 4th, 2017.

The content of this workshop will be a condensed version of a workshop Data
Carpentry teaches in 2 days that introduces best practices for [Reproducible
Science with R](http://www.datacarpentry.org/rr-workshop.). This will be an opportunity for you to learn more about this
topic, and to experience the teaching style of Data Carpentry workshops.

## Setup

Make sure you have installed:

- [R](https://cran.r-project.org)
- [RStudio](https://www.rstudio.com/products/rstudio/download/#download)

and then install the **`tidyverse`**, **`rmarkdown`**, and **`testthat`** packages. From the R terminal:

```r
install.packages(c("tidyverse", "rmarkdown", "testthat"))
```

For this workshop, we will use the gapminder dataset. We will provide you with the datasets as needed, but if you wish to explore this dataset further, we encourage you to install Jenny Bryan's package of the same name:

```r
install.packages("gapminder")
```

## R Markdown demonstration files

* [01-mot-rep-soln.Rmd](https://raw.githubusercontent.com/fmichonneau/2017-useR-reproducibility/master/material/01-mot-rep-soln.Rmd)
* [02-extend-soln.Rmd](https://raw.githubusercontent.com/fmichonneau/2017-useR-reproducibility/master/material/02-extend-soln.Rmd)
* [03-more-lit-prog.Rmd](https://raw.githubusercontent.com/fmichonneau/2017-useR-reproducibility/master/material/03-more-lit-prog.Rmd)

* [gapminder-5060.csv](https://github.com/fmichonneau/2017-useR-reproducibility/raw/master/material/data/gapminder-5060.csv)
* [gapminder-7080.csv](https://github.com/fmichonneau/2017-useR-reproducibility/raw/master/material/data/gapminder-7080.csv)
* [gapminder-90plus.csv](https://github.com/fmichonneau/2017-useR-reproducibility/raw/master/material/data/gapminder-90plus.csv)
* [gapminder.csv](https://github.com/fmichonneau/2017-useR-reproducibility/raw/master/material/data/gapminder.csv)


You need to setup your working directory such that the Rmd files are at the root of it, and the CSV files are in a `data` foder:

```
+--- data/
|    |
|    +--- gapminder-5060.csv
|    +--- gapminder-7080.csv
|    +--- gapminder-90plus.csv
|    +--- gapminder.csv
|
+--- 01-mot-rep-soln.Rmd
+--- 02-extend-soln.Rmd
+--- 03-more-lit-prog.Rmd

```
