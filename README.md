# medepir: MEthylation DEconvoluation PIpeline in R

Package {medepir} (MEthylation DEconvoluation PIpeline in R) provides practical implementation of recommended guidelines for inference of cell-type proportions with confounders, based on non-negative matrix factorization of DNA methylation data. 

Decamps, C., Privé, F., Bacher, R. et al. Guidelines for cell-type heterogeneity quantification based on a comparative analysis of reference-free DNA methylation deconvolution software. BMC Bioinformatics 21, 16 (2020). https://doi.org/10.1186/s12859-019-3307-2

## Installation

To get the current version from GitHub:

```R
remotes::install_github("bcm-uga/medepir")
```

To also build vignettes, use:

```R
# Take 1-5 min to build
remotes::install_github(
  "bcm-uga/medepir", build_opts = c("--no-resave-data", "--no-manual"))
                        
# To see the two vignettes:
vignette("simulations", package = "medepir")
vignette("deconvolution", package = "medepir")
```
