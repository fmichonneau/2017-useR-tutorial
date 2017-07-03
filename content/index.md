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

and then install the **`tidyverse`** and **`rmarkdown`** packages. From the R terminal:

```r
install.packages(c("tidyverse", "rmarkdown"))
```

For this workshop, we will use the gapminder dataset. We will provide you with the datasets as needed, but if you wish to explore this dataset further, we encourage you to install Jenny Bryan's package of the same name:

```r
install.packages("gapminder")
```

## RMarkdown demonstration file

* [rr-demo.Rmd](https://raw.githubusercontent.com/fmichonneau/2017-useR-reproducibility/master/material/rr-demo.Rmd)
* [gapminder.csv](https://github.com/fmichonneau/2017-useR-reproducibility/raw/master/material/data/gapminder.csv)


You need to setup your working directory such that the Rmd file is at the root of it, and the CSV file is in a `data` foder:

```
+--- data/
|    |
|    +--- gapminder.csv
|
+--- rr-demo.Rmd
```
