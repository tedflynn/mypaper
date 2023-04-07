
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypaper

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh///master?urlpath=rstudio)

This repository contains the data and code for our paper:

> Authors, (YYYY). *Title of your paper goes here*. Name of journal/book
> <https://doi.org/xxx/xxx>

Our pre-print is online here:

> Authors, (YYYY). *Title of your paper goes here*. Name of
> journal/book, Accessed 07 Apr 2023. Online at
> <https://doi.org/xxx/xxx>

### How to cite

Please cite this compendium as:

> Authors, (2023). *Compendium of R code and data for Title of your
> paper goes here*. Accessed 07 Apr 2023. Online at
> <https://doi.org/xxx/xxx>

## Contents

The **analysis** directory contains:

- [:file_folder: paper](/analysis/paper): Quarto source document for
  manuscript. Includes code to reproduce the figures and tables
  generated by the analysis. It also has a rendered version,
  `paper.docx`, suitable for reading (the code is replaced by figures
  and tables in this file)
- [:file_folder: data](/analysis/data): Data used in the analysis.
- [:file_folder: figures](/analysis/figures): Plots and other
  illustrations
- [:file_folder:
  supplementary-materials](/analysis/supplementary-materials):
  Supplementary materials including notes and other documents prepared
  and collected during the analysis.

## How to run in your browser or download and run locally

This research compendium has been developed using the statistical
programming language R. To work with the compendium, you will need
installed on your computer the [R
software](https://cloud.r-project.org/) itself and optionally [RStudio
Desktop](https://rstudio.com/products/rstudio/download/).

You can download the compendium as a zip from from this URL:
[master.zip](/archive/master.zip). After unzipping: - open the `.Rproj`
file in RStudio - run `devtools::install()` to ensure you have the
packages this analysis depends on (also listed in the
[DESCRIPTION](/DESCRIPTION) file). - finally, open
`analysis/paper/paper.Rmd` and knit to produce the `paper.docx`, or run
`rmarkdown::render("analysis/paper/paper.qmd")` in the R console

### Licenses

**Text and figures :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Code :** See the [DESCRIPTION](DESCRIPTION) file

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

### Contributions

We welcome contributions from everyone. Before you get started, please
see our [contributor guidelines](CONTRIBUTING.md). Please note that this
project is released with a [Contributor Code of Conduct](CONDUCT.md). By
participating in this project you agree to abide by its terms.