
# BMix <img src='man/figures/logo.png' align="right" height="139" />

<!-- badges: start -->

[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-stable-green.svg)](https://www.tidyverse.org/lifecycle/#stable)
[![R-CMD-check](https://github.com/caravagn/BMix/workflows/R-CMD-check/badge.svg)](https://github.com/caravagn/BMix/actions)

<!-- badges: end -->

`BMix` provides univariate Binomial and Beta-Binomial mixture models.
Count-based mixtures can be used in a variety of settings, for instance
to model genome sequencing data of somatic mutations in cancer.

`BMix` fits these mixtures by maximum likelihood exploiting the
Expectation Maximization algorithm. Model selection for the number of
mixture components is by the Integrated Classification Likelihood, an
extension of the Bayesian Information Criterion that includes the
entropy of the latent variables.

#### Help and support

[![](https://img.shields.io/badge/GitHub%20Pages-https://caravagnalab.github.io/BMix/-yellow.svg)](https://caravagnalab.github.io/BMix)

------------------------------------------------------------------------

#### Installation

You can install the released version of `BMix` from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("caravagnalab/BMix")
```

------------------------------------------------------------------------

#### Copyright and contacts

Giulio Caravagna. Cancer Data Science (CDS) Laboratory.

[![](https://img.shields.io/badge/Email-gcaravagn@gmail.com-steelblue.svg)](mailto:gcaravagn@gmail.com)
[![](https://img.shields.io/badge/CDS%20Lab%20Github-caravagnalab-seagreen.svg)](https://github.com/caravagnalab)
[![](https://img.shields.io/badge/CDS%20Lab%20webpage-https://www.caravagnalab.org/-red.svg)](https://www.caravagnalab.org/)
