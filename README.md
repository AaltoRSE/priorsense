
<!-- README.md is generated from README.Rmd. Please edit that file -->
<img src='man/figures/logo.png' align="right" height="139" />

# priorsense

<!-- badges: start -->
[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental) [![CRAN status](https://www.r-pkg.org/badges/version/priorsense)](https://CRAN.R-project.org/package=priorsense) [![R-CMD-check](https://github.com/n-kall/priorsense/workflows/R-CMD-check/badge.svg)](https://github.com/n-kall/priorsense/actions) <!-- badges: end -->

## Overview

priorsense provides tools for prior diagnostics and sensitivity analysis.

It currently includes functions for performing power-scaling sensitivity analysis on Stan models. This way to check how sensitive a posterior is to perturbations of the prior and likelihood and diagnose the cause of sensitivity. For efficient computation, power-scaling sensitivity analysis relies on Pareto smoothed importance sampling (Vehtari et al., 2019) and importance weighted moment matching (Paananen et al., 2021).

Power-scaling sensitivity analysis and priorsense are described in Kallioinen et al. (2021).

## Installation

Download the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("n-kall/priorsense")
```

## References

Kallioinen, N., Paananen, T., Bürkner P-C., and Vehtari, A. (2021). Detecting and diagnosing prior and likelihood sensitivity with power-scaling. preprint [arXiv:2107.14054](https://arxiv.org/abs/2107.14054)

Paananen, T., Piironen, J., Bürkner P-C., and Vehtari, A. (2021). Implicitly adaptive importance sampling. Statistics and Computing 31, 16. <https://doi.org/10.1007/s11222-020-09982-2>

Vehtari, A., Simpson, D., Gelman, A., Yao, Y., and Gabry, J. (2019). Pareto smoothed importance sampling. preprint [arXiv:1507.02646](https://arxiv.org/abs/1507.02646)
