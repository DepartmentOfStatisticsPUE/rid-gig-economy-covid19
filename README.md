# Repo for the paper "COVID-19 and the gig economy in Poland"

## Basic info

Data and codes for the paper "COVID-19 and the gig economy in Poland" (Arxiv preprint: TBA) by:

+ Beręsewicz Maciej -- Poznań University of Economics and Business, Poland; Statistical Office in Poznań, Poland
+ Nikulin Dagmara -- Gdańsk University of Technology, Poland
The structure of the repo is as follows:

+ `data/` -- folder with four datasets: 

        + `gig-montly-stats-new.csv`
        + `gig-table2-halfyear-demo-stats.csv`
        + `gig-table3-halfyear-region-stats.csv`
        + `covid-in-poland.csv`
        
+ `figures/` -- figures prepared for the paper
+ `notebooks/` -- notebooks with analysis. Currently only one notebok `analysis.Rmd`


## Acknowledgements

The study was conducted within the research project *Economics in the face of the New Economy* financed within the Regional Initiative for Excellence programme of the Minister of Science and Higher Education of Poland, years 2019-2022, grant no. 004/RID/2018/19, financing 3,000,000 PLN (for Maciej Beręsewicz).

## Session info

```{r}
> sessionInfo()
R version 3.6.1 (2019-07-05)
Platform: x86_64-apple-darwin15.6.0 (64-bit)
Running under: OS X  11.4

Matrix products: default
LAPACK: /Library/Frameworks/R.framework/Versions/3.6/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] tidyquant_1.0.3            quantmod_0.4.18            TTR_0.24.2                 PerformanceAnalytics_2.0.4
 [5] xtable_1.8-4               broom_0.7.8                janitor_2.1.0              CausalImpact_1.2.7        
 [9] bsts_0.9.7                 xts_0.12.1                 zoo_1.8-9                  BoomSpikeSlab_1.2.4       
[13] Boom_0.9.7                 MASS_7.3-54                lubridate_1.7.10           forcats_0.5.1             
[17] stringr_1.4.0              dplyr_1.0.7                purrr_0.3.4                readr_1.4.0               
[21] tidyr_1.1.3                tibble_3.1.2               ggplot2_3.3.5              tidyverse_1.3.1           

loaded via a namespace (and not attached):
 [1] httr_1.4.2        sass_0.4.0        jsonlite_1.7.2    splines_3.6.1     modelr_0.1.8      bslib_0.2.5.1    
 [7] assertthat_0.2.1  cellranger_1.1.0  yaml_2.2.1        pillar_1.6.1      backports_1.2.1   lattice_0.20-44  
[13] glue_1.4.2        quadprog_1.5-8    digest_0.6.27     rvest_1.0.0       snakecase_0.11.0  colorspace_2.0-2 
[19] htmltools_0.5.1.1 Matrix_1.3-4      pkgconfig_2.0.3   haven_2.4.1       scales_1.1.1      mgcv_1.8-36      
[25] generics_0.1.0    farver_2.1.0      ellipsis_0.3.2    withr_2.4.2       cli_3.0.0         magrittr_2.0.1   
[31] crayon_1.4.1      readxl_1.3.1      evaluate_0.14     fs_1.5.0          fansi_0.5.0       nlme_3.1-152     
[37] xml2_1.3.2        tools_3.6.1       hms_1.1.0         lifecycle_1.0.0   munsell_0.5.0     reprex_2.0.0     
[43] compiler_3.6.1    jquerylib_0.1.4   rlang_0.4.11      grid_3.6.1        rstudioapi_0.13   labeling_0.4.2   
[49] rmarkdown_2.9     gtable_0.3.0      DBI_1.1.1         curl_4.3.2        R6_2.5.0          knitr_1.33       
[55] utf8_1.2.1        Quandl_2.10.0     stringi_1.6.2     Rcpp_1.0.7        vctrs_0.3.8       dbplyr_2.1.1     
[61] tidyselect_1.1.1  xfun_0.24        
```
