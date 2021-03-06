spplit
======



[![R-check](https://github.com/sckott/spplit/workflows/R-check/badge.svg)](https://github.com/sckott/spplit/actions/)

`spplit` - connect species occurrence data to literature

docs: <https://sckott.github.io/spplit/>

* `spocc::occ()` to get occurrence data
* `sp_lit_meta()` gather metadata from taxonomic names from occurrence data
* `sp_lit_text()` gather full text from literature metadata
* `sp_lit_names()` extract names from full text
* `sp_parse_names()` parse names into components

## Install

install `rgbif` and `spocc`, then install `spplit`


```r
remotes::install_github(c("ropensci/namext"))
remotes::install_github("sckott/spplit")
```


```r
library("spplit")
```

## Meta

* A collaboration with [California Academy of Sciences](http://www.calacademy.org/)
* Please [report any issues or bugs](https://github.com/sckott/spplit/issues)
* License: MIT
* Please note that the spplit project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.
