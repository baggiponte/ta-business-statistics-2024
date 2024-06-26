# 🎓 Business Statistics A.Y. 2023-2024

Welcome to the tutorials of the Business Statistics course (AY 2023-2024). This repository contains the code that is presented at each lecture.

The code is stored in `Rmarkdown` files. These are notebooks that alternate code and descriptions. It's slightly different from a regular script (ending in `.R`), but you can treat it in the same way. For all that matters, treat it as a script with a nicer way to combine code and text.

To run the notebooks, you should make sure the `{rmarkdown}` package is installed.

```r
install.packages("rmarkdown")
```

There will be 8 classes, divided as follows:

* **Part 1** (two classes): Introduction to R and programming.
* **Part 2** (three classes): Clustering methods.
* **Part 3** (three classes): Time series analysis.

## Part 1: Introduction to R Programming

This part provides an overview of the R programming language and introduce the basic components of R.

1. Installing R and RStudio + Elements of R: working with strings, numbers, and operators
  - Introduction to R and RStudio
  - How to run R code in the Console
  - Persist code in R scripts and run them
  - Literate programming in RMarkdown files
  - Setting up your R environment (installing packages, setting working directory, etc.)
  - R syntax basics (comments, variables, data types, operators)
  - Using R as a calculator (basic arithmetic, logical operations, comparison operators)
  - Basic data types: strings
  - Define your own functions
  - R built-in functions for data manipulation (sum, mean, max, min, etc.)

2. Vectors, Matrices, and DataFrames + Introduction to statistical computations
  - Creating and working with vectors
  - Creating and accessing subsets of data in R (indexing, slicing)
  - Apply functions to vectors
  - Sample from random variables
  - `data.frame`s introduction
  - `factor` datatypes.
  - Introduction to the `{tidyverse}` and `tibble`s.
  - Introduction to exploratory data analysis and data visualisation with `{ggplot2}`

Appendices:
  - Matrices and Lists, as well as how to index and perform operations on them.
  - Control structures in R (if-else statements, loops)
  - Elements of the `{tidyverse}`:
    - Plotting with `{ggplot2}`
    - Data manipulation with `{dplyr}`
    - The pipe operator
