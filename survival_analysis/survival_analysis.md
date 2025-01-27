---
title: "Time to event versus Logistic Regression"
author: "Hedwig Nora Nordlinder"
date: "January 27, 2025"
output:
  html_document:
    toc: true
    toc_float: true
    theme: flatly
    highlight: tango
    code_folding: show
tags: [R, survival analysis]
---



## Introduction

Brief introduction to your blog post topic. What will readers learn? Why is this important?

## Data Preparation


``` r
# Your data preparation code here
# Example:
# data <- read_csv("your_data.csv")
```

## Analysis

### Exploratory Data Analysis


``` r
# Your exploratory analysis code here
```

### Key Findings

Discuss your main findings here. You can include:

- Important observations
- Unexpected results
- Practical implications

## Visualizations


``` r
# Your visualization code here
# Example:
# ggplot(data, aes(x = x, y = y)) +
#   geom_point() +
#   theme_minimal()
```

## Conclusions

Summarize your key takeaways and potential next steps.

## References

<!-- If you're using citations, they'll appear here -->

## Session Info


``` r
sessionInfo()
```

```
## R version 4.0.5 (2021-03-31)
## Platform: x86_64-redhat-linux-gnu (64-bit)
## Running under: Fedora 34 (Workstation Edition)
## 
## Matrix products: default
## BLAS/LAPACK: /usr/lib64/libflexiblas.so.3.1
## 
## locale:
##  [1] LC_CTYPE=en_GB.UTF-8       LC_NUMERIC=C               LC_TIME=en_GB.UTF-8        LC_COLLATE=en_GB.UTF-8    
##  [5] LC_MONETARY=en_GB.UTF-8    LC_MESSAGES=en_GB.UTF-8    LC_PAPER=en_GB.UTF-8       LC_NAME=C                 
##  [9] LC_ADDRESS=C               LC_TELEPHONE=C             LC_MEASUREMENT=en_GB.UTF-8 LC_IDENTIFICATION=C       
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## other attached packages:
##  [1] kableExtra_1.4.0 knitr_1.48       forcats_1.0.0    stringr_1.5.0    dplyr_1.1.4      purrr_1.0.1     
##  [7] readr_2.1.3      tidyr_1.3.0      tibble_3.2.1     ggplot2_3.4.4    tidyverse_1.3.2 
## 
## loaded via a namespace (and not attached):
##  [1] tidyselect_1.2.0    xfun_0.47           haven_2.5.3         gargle_1.2.1        colorspace_2.1-0   
##  [6] vctrs_0.6.4         generics_0.1.2      viridisLite_0.4.2   htmltools_0.5.8.1   yaml_2.3.7         
## [11] utf8_1.2.4          rlang_1.1.2         pillar_1.9.0        withr_2.5.2         glue_1.6.2         
## [16] DBI_1.1.3           dbplyr_2.3.0        modelr_0.1.10       readxl_1.4.1        lifecycle_1.0.4    
## [21] munsell_0.5.0       gtable_0.3.4        cellranger_1.1.0    rvest_1.0.3         evaluate_0.19      
## [26] tzdb_0.4.0          fastmap_1.1.1       fansi_1.0.5         broom_1.0.3         backports_1.4.1    
## [31] scales_1.2.1        googlesheets4_1.0.1 jsonlite_1.8.7      systemfonts_1.0.4   fs_1.5.2           
## [36] hms_1.1.2           digest_0.6.31       stringi_1.7.12      grid_4.0.5          cli_3.6.1          
## [41] tools_4.0.5         magrittr_2.0.3      crayon_1.5.0        pkgconfig_2.0.3     ellipsis_0.3.2     
## [46] xml2_1.3.3          reprex_2.0.2        googledrive_2.0.0   lubridate_1.9.1     timechange_0.2.0   
## [51] svglite_2.1.1       assertthat_0.2.1    rmarkdown_2.28      httr_1.4.4          rstudioapi_0.15.0  
## [56] R6_2.5.1            compiler_4.0.5
```
