# Reproductive phenotype predicts adult bite-force performance in sex-reversed dragons (<i>Pogona vitticeps</i>)  

Author(s): [Marc EH Jones](mailto:marc.jones@ucl.ac.uk) and [Natalie Cooper](mailto:natalie.cooper.@nhm.ac.uk)

This repository contains all the code and some data used in the [paper - link will appear here](xxx). 

To cite the paper: 
> 
Jones MEH, Pistevos JCA, Cooper N, Lappin AK, Georges A, Hutchinson MN, Holleley CE. 2020. Reproductive phenotype predicts adult bite-force performance in sex-reversed dragons (<i>Pogona vitticeps<i/>). Journal of Experimental Zoology A



To cite this repo: 
> 
Jones, M. E. H. & Cooper, N. 2020. Code time stamped by Zenodo [doi to be added on acceptance] 


## Data
The cleaned data are available from the [xxx]()

For reproducibility purposes the data needed to rerun all the analyses is found in the `data/` folder. Note that I cannot share the raw data as it is not all published yet and does not belong solely to me.

* `data/` should include `pogona-data.csv`. This is the dataset required to run the analyses.

If you use the cleaned data please cite as follows: 
> ???

-------
## Data wrangling
Prior to analyses some data wrangling occurred. 
The script is available for reference but I cannot share the raw data.
* 01-data-wrangling.R

-------
## Analyses
The analysis code is divided into `.Rmd` files that run the analyses and plot the figures for each section of the paper/supplementary materials.
Note that throughout I've commented out `ggsave` commands so you don't clog your machine up with excess plots you don't need.

- **02-summarising-differences.Rmd**
- **03-genotype-differences.Rmd**
- **04-allometry.Rmd**
- **05-bite-force-scaling.Rmd**
- **06-pca-plot.Rmd**
- **07-temperature.Rmd**
- **08-genotype-differences-malefemale.Rmd**
- **09-transducer.Rmd**

-------
## Session Info
For reproducibility purposes, here is the output of `devtools::session_info()` used to perform the analyses in the publication.

    ─ Session info ─────────────────────────────────────────────────────────────────
    setting  value                       
    version  R version 3.5.2 (2018-12-20)
    os       OS X El Capitan 10.11.6     
    system   x86_64, darwin15.6.0        
    ui       RStudio                     
    language (EN)                        
    collate  en_GB.UTF-8                 
    ctype    en_GB.UTF-8                 
    tz       Europe/London               
    date     2019-11-05                  

    ─ Packages ───────────────────────────────────────────────────────────────────── 
    package      * version date       lib source                               
    abind          1.4-5   2016-07-21 [1] CRAN (R 3.5.0)                       
    assertthat     0.2.1   2019-03-21 [1] CRAN (R 3.5.2)                       
    backports      1.1.4   2019-04-10 [1] CRAN (R 3.5.2)                       
    broom        * 0.5.2   2019-04-07 [1] CRAN (R 3.5.2)                       
    callr          3.3.1   2019-07-18 [1] CRAN (R 3.5.2)                       
    car          * 3.0-2   2018-08-23 [1] CRAN (R 3.5.0)                       
    carData      * 3.0-2   2018-09-30 [1] CRAN (R 3.5.0)                       
    cellranger     1.1.0   2016-07-27 [1] CRAN (R 3.5.0)                       
    cli            1.1.0   2019-03-19 [1] CRAN (R 3.5.2)                       
    colorspace     1.4-1   2019-03-18 [1] CRAN (R 3.5.2)                       
    crayon         1.3.4   2017-09-16 [1] CRAN (R 3.5.0)                       
    curl           4.1     2019-09-16 [1] CRAN (R 3.5.2)                       
    data.table     1.12.0  2019-01-13 [1] CRAN (R 3.5.2)                       
    desc           1.2.0   2018-05-01 [1] CRAN (R 3.5.0)                       
    devtools       2.0.1   2018-10-26 [1] CRAN (R 3.5.2)                       
    digest         0.6.20  2019-07-04 [1] CRAN (R 3.5.2)                       
    dplyr        * 0.8.3   2019-07-04 [1] CRAN (R 3.5.2)                       
    forcats      * 0.4.0   2019-02-17 [1] CRAN (R 3.5.2)                       
    foreign        0.8-71  2018-07-20 [1] CRAN (R 3.5.2)                       
    fs             1.3.1   2019-05-06 [1] CRAN (R 3.5.2)                       
    generics       0.0.2   2018-11-29 [1] CRAN (R 3.5.0)                       
    ggConvexHull * 0.1.0   2019-02-28 [1] Github (cmartin/ggConvexHull@e05904a)
    ggfortify    * 0.4.5   2018-05-26 [1] CRAN (R 3.5.0)                       
    ggplot2      * 3.2.1   2019-08-10 [1] CRAN (R 3.5.2)                       
    ggpubr       * 0.2.3   2019-09-03 [1] CRAN (R 3.5.2)                       
    ggsignif       0.6.0   2019-08-08 [1] CRAN (R 3.5.2)                       
    glue           1.3.1   2019-03-12 [1] CRAN (R 3.5.2)                       
    gridExtra      2.3     2017-09-09 [1] CRAN (R 3.5.0)                       
    gtable         0.3.0   2019-03-25 [1] CRAN (R 3.5.2)                       
    haven          2.1.1   2019-07-04 [1] CRAN (R 3.5.2)                       
    here         * 0.1     2017-05-28 [1] CRAN (R 3.5.0)                       
    hms            0.5.1   2019-08-23 [1] CRAN (R 3.5.2)                       
    httr           1.4.1   2019-08-05 [1] CRAN (R 3.5.2)                       
    jsonlite       1.6     2018-12-07 [1] CRAN (R 3.5.0)                       
    knitr        * 1.24    2019-08-08 [1] CRAN (R 3.5.2)                       
    lattice        0.20-38 2018-11-04 [1] CRAN (R 3.5.2)                       
    lazyeval       0.2.2   2019-03-15 [1] CRAN (R 3.5.2)                       
    lifecycle      0.1.0   2019-08-01 [1] CRAN (R 3.5.2)                       
    lubridate      1.7.4   2018-04-11 [1] CRAN (R 3.5.0)                       
    magrittr     * 1.5     2014-11-22 [1] CRAN (R 3.5.0)                       
    memoise        1.1.0   2017-04-21 [1] CRAN (R 3.5.0)                       
    modelr         0.1.5   2019-08-08 [1] CRAN (R 3.5.2)                       
    munsell        0.5.0   2018-06-12 [1] CRAN (R 3.5.0)                       
    nlme           3.1-137 2018-04-07 [1] CRAN (R 3.5.2)                       
    openxlsx       4.1.0   2018-05-26 [1] CRAN (R 3.5.0)                       
    patchwork    * 0.0.1   2018-11-16 [1] Github (thomasp85/patchwork@fd7958b) 
    pillar         1.4.2   2019-06-29 [1] CRAN (R 3.5.2)                       
    pkgbuild       1.0.2   2018-10-16 [1] CRAN (R 3.5.0)                       
    pkgconfig      2.0.2   2018-08-16 [1] CRAN (R 3.5.0)                       
    pkgload        1.0.2   2018-10-29 [1] CRAN (R 3.5.0)                       
    prettyunits    1.0.2   2015-07-13 [1] CRAN (R 3.5.0)                       
    processx       3.4.1   2019-07-18 [1] CRAN (R 3.5.2)                       
    ps             1.3.0   2018-12-21 [1] CRAN (R 3.5.0)                       
    purrr        * 0.3.2   2019-03-15 [1] CRAN (R 3.5.2)                       
    R6             2.4.0   2019-02-14 [1] CRAN (R 3.5.2)                       
    Rcpp           1.0.2   2019-07-25 [1] CRAN (R 3.5.2)                       
    readr        * 1.3.1   2018-12-21 [1] CRAN (R 3.5.0)                       
    readxl         1.3.1   2019-03-13 [1] CRAN (R 3.5.2)                       
    remotes        2.0.2   2018-10-30 [1] CRAN (R 3.5.0)                       
    rio            0.5.16  2018-11-26 [1] CRAN (R 3.5.0)                       
    rlang          0.4.0   2019-06-25 [1] CRAN (R 3.5.2)                       
    rprojroot      1.3-2   2018-01-03 [1] CRAN (R 3.5.0)                       
    rstudioapi     0.10    2019-03-19 [1] CRAN (R 3.5.2)                       
    rvest          0.3.4   2019-05-15 [1] CRAN (R 3.5.2)                       
    scales         1.0.0   2018-08-09 [1] CRAN (R 3.5.0)                       
    sessioninfo    1.1.1   2018-11-05 [1] CRAN (R 3.5.0)                       
    stringi        1.4.3   2019-03-12 [1] CRAN (R 3.5.2)                       
    stringr      * 1.4.0   2019-02-10 [1] CRAN (R 3.5.2)                       
    tibble       * 2.1.3   2019-06-06 [1] CRAN (R 3.5.2)                       
    tidyr        * 1.0.0   2019-09-11 [1] CRAN (R 3.5.2)                       
    tidyselect     0.2.5   2018-10-11 [1] CRAN (R 3.5.0)                       
    tidyverse    * 1.2.1   2017-11-14 [1] CRAN (R 3.5.0)                       
    usethis        1.4.0   2018-08-14 [1] CRAN (R 3.5.0)                       
    vctrs          0.2.0   2019-07-05 [1] CRAN (R 3.5.2)                       
    withr          2.1.2   2018-03-15 [1] CRAN (R 3.5.0)                       
    xfun           0.9     2019-08-21 [1] CRAN (R 3.5.2)                       
    xml2           1.2.2   2019-08-09 [1] CRAN (R 3.5.2)                       
    yaml           2.2.0   2018-07-25 [1] CRAN (R 3.5.0)                       
    zeallot        0.1.0   2018-01-28 [1] CRAN (R 3.5.0)                       
    zip            1.0.0   2017-04-25 [1] CRAN (R 3.5.0)                       
              
## Checkpoint for reproducibility
To rerun all the code with packages as they existed on CRAN at time of our analyses we recommend using the `checkpoint` package, and running this code prior to the analysis:

```{r}
checkpoint("2020-01-23")
```
