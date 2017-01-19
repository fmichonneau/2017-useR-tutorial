---
title: "Data Carpentry: Open and Reproducible Research with R"
author: |
   | Francois Michonneau^1^ and Tracy K. Teal^2^
   |
   | 1. University of Florida
   | 2. Data Carpentry
institute:
   - $^1$Whitney Laboratory for Marine Bioscience
   - $^2$Data Carpentry
output:
   - html_document
   - pdf_document
#bibliography: biblioExample.bib
nocite: |
  @ref2, @ref3
---

**Keywords**: Reproducible Research, RMarkdown, Open Science, Data Carpentry, Github

## Tutorial goals

The goal of this tutorial is to teach participants the skills and perspectives
needed to conduct open research with R, including literate programming and best
practices in sharing and publishing code and data. We will focus on how to make
the work navigable, interpretable, and repeatable by others. This tutorial is
modified from the Data Carpentry "Reproducible Research with R" workshop, and we
will focus on an exemplar project to model the workflow of going from code and
data to a published, archived product.


## Tutorial objectives and outline

This tutorial is a module of the Data Carpentry "Reproducible Research with R"
workshop, and we will focus on an exemplar project to model the workflow of
going from code and data to a published product.

The objectives (in bold) and outline for the workshop are:

* **Review of the basics of working with RMarkdown to generate high quality
  reports:** how to use code chunks, inline code; how to generate figures, how to
  export to HTML, PDF, Word documents; how to use references (bibliography,
  references to figures and tables).
* **Understand the benefits of file organization to automate and facilitate report
  creation:** how to organize files for inputs and outputs to use fully automated
  workflow to generate reports.
* **Use best practices to modularize code and text for complex reports:** how to
  separate code from text, how to organize code into functions, how to leverage
  package development tools to test and document code.
* **Learn to use Git and Github in RStudio:** how to use the RStudio interface with
  GitHub to keep track of changes in the code and collaborate with others.
* **Learn best practices for sharing code:** how to write code that can be used
  by other people, how to document dependencies.
* **Understand available software licenses and issues around data licensing:**
  describe common open source licenses used for code and data, understand
  differences and implications for code and data reuse.
* **Publishing and archive reports and datasets using R packages:** how to use
  platforms for data and code publishing and archiving, how to automate the
  process using R packages.
* **Learn about and create an ORCID to track research products:** learn about the
  benefits of using ORCID to identify authors.

Lessons:

* <http://www.datacarpentry.org/rr-literate-programming/02-literate-programming/>
* <http://www.datacarpentry.org/rr-literate-programming/03-explore-knitr/>
* <http://www.datacarpentry.org/rr-version-control/03-git-in-rstudio/>
* <http://www.datacarpentry.org/rr-publication/01-publication/>


## Justification for running the tutorial at useR! 2017

As an increasing number of people are using R to conduct research, it is
possible to share and publish this code and data to enable reproducible research
and advance research progress. Additionally there is increasing acceptance and
interest in ‘open’ research practices, where code and data are shared as a part
of the ongoing or final research product.  In Data Carpentry surveys of the
skills scientists are looking to learn, people with some R experience are most
interested in learning how to distribute, share and publish their code and data
using RMarkdown. In particular, they are interested in learning about literate
programming, sharing code through github, and publishing code and data in
repositories like FigShare. These skills and perspectives are necessary for open
research and are clear next steps in learning for best practices and effective
research R. We expect that many participants at UseR! will be looking for
opportunities to learn these skills.

The active learning style of Data Carpentry workshops has been shown to be
effective in teaching people the skills and perspectives needed to work with
data. The vast majority (>90%) of participants responding to post-workshop
surveys say that participating in the workshop was worth their time and led to
improvements in their data management and data analysis skills. Additionally 94%
of participants agree or strongly agree that they would recommend a workshop to
a friend or colleague (reference: [1])


## Description of the tutorial

In most domains of research & industry there is an increasing capacity to
generate data and an increasing knowledge of how to analyze this data using
programming languages such as R. With this increasing capacity, is the potential
to more effectively communicate, share and publish both the results of these
analyses and the complete workflow for open research. However, many people do
not yet have the skills or know best practices to effectively share and
disseminate research products.

This tutorial is for people who are looking to move towards open research
practices and want to learn the next steps in how to structure code and data,
share these research products and publish this for broader dissemination, reuse
and attribution.  In this tutorial participants will learn how to generate
documents with literate programming, share them via github, use appropriate
licenses, and publish data and code research products. They will learn how to
write RMarkdown, share code via github, and publish and track data and code
research products.


## Pre-requisites

Workshop participants should have a familiarity with working in R.

## Potential attendees

Many people in academia or in other organizations are being required to, or see
the value in sharing and publishing their research products and
process. Potential attendees are people who are conducting work in R and are
interested in learning how to share and publish their code and data for open and
reproducible research.

## Instructor biograph(y/ies) or link to online profile(s)

Tracy Teal is a co-founder and the Executive Director of Data Carpentry. She has
taught over 30 workshops teaching people to work more effectively with data and
helped develop curriculum on Reproducible Research and domain-specific
curriculum for working with ecology data, genomic data, and geospatial data.

Francois Michonneau is a post-doctoral researcher at the University of Florida
interested in using and teaching about best practices in Reproducible
Research. He has taught over 15 workshops and developed a semester-long course
to help people learn how to use R to work with their data.


## References

1 Jordan, Kari. (2016). Data Carpentry Assessment Report: Analysis of
Post-Workshop Survey Results. Zenodo. doi: [10.5281/zenodo.165858](https://doi.org/10.5281/zenodo.165858)
