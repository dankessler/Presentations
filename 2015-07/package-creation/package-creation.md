Creating Your Own R Package
========================================================
author: Jeff Shane
date: 07/09/2015

Purpose
========================================================

Why bother making your own package?

- Reproducibility
- Cohesive set of functions
- Sharing
- Documentation

Resources
========================================================

http://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/

Getting Started
========================================================

Installing `devtools` and `roxygen`


```r
install.packages("devtools")
library("devtools")
devtools::install_github("klutometis/roxygen")
library(roxygen2)
```

