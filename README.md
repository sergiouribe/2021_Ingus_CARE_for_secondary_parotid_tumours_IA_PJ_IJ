# CARE Parotid tumours

Reporting quality of case reports about secondary parotid neoplasms from distantant metastasis assessed by CARE guidelines

Data analysis script

Original data: https://docs.google.com/spreadsheets/d/e/2PACX-1vRKPzFe2lbF87DNe9SBjuaIb5iMb4nCmgvfdyT4v-NjK-BZBR-HkUIUdgiML3t30EqQ1RCep0sExatK/pub?output=csv


sessionInfo()

> sessionInfo()
R version 4.0.4 (2021-02-15)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Pop!_OS 21.10

Matrix products: default
BLAS:   /usr/lib/x86_64-linux-gnu/blas/libblas.so.3.9.0
LAPACK: /usr/lib/x86_64-linux-gnu/lapack/liblapack.so.3.9.0

locale:
 [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C               LC_TIME=en_GB.UTF-8        LC_COLLATE=en_US.UTF-8     LC_MONETARY=en_GB.UTF-8   
 [6] LC_MESSAGES=en_US.UTF-8    LC_PAPER=en_GB.UTF-8       LC_NAME=C                  LC_ADDRESS=C               LC_TELEPHONE=C            
[11] LC_MEASUREMENT=en_GB.UTF-8 LC_IDENTIFICATION=C       

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] dlookr_0.4.2    janitor_2.0.1   gtsummary_1.5.0 forcats_0.5.1   stringr_1.4.0   dplyr_1.0.7     purrr_0.3.4     readr_2.1.1     tidyr_1.1.4    
[10] tibble_3.1.6    ggplot2_3.3.5   tidyverse_1.3.0

loaded via a namespace (and not attached):
  [1] colorspace_2.0-2     gitcreds_0.1.1       ellipsis_0.3.2       class_7.3-18         rio_0.5.16           snakecase_0.11.0     htmlTable_2.3.0     
  [8] base64enc_0.1-3      fs_1.5.0             rstudioapi_0.13      proxy_0.4-26         farver_2.1.0         bit64_4.0.5          mvtnorm_1.1-3       
 [15] fansi_0.5.0          lubridate_1.8.0      xml2_1.3.3           splines_4.0.4        extrafont_0.17       libcoin_1.0-9        knitr_1.36          
 [22] Formula_1.2-4        jsonlite_1.7.2       gt_0.3.1             broom_0.7.10.9000    Rttf2pt1_1.3.8       cluster_2.1.1        dbplyr_2.0.0        
 [29] png_0.1-7            compiler_4.0.4       httr_1.4.2           backports_1.3.0      assertthat_0.2.1     Matrix_1.3-2         fastmap_1.1.0       
 [36] cli_3.1.0            hrbrthemes_0.8.0     htmltools_0.5.2.9000 tools_4.0.4          partykit_1.2-15      gtable_0.3.0         glue_1.5.1          
 [43] Rcpp_1.0.7           carData_3.0-4        jquerylib_0.1.3      cellranger_1.1.0     vctrs_0.3.8          extrafontdb_1.0      broom.helpers_1.4.0 
 [50] inum_1.0-4           xfun_0.28            openxlsx_4.2.3       rvest_1.0.2          lifecycle_1.0.1      pacman_0.5.1         RcmdrMisc_2.7-1     
 [57] MASS_7.3-53.1        zoo_1.8-9            scales_1.1.1         vroom_1.5.7          hms_1.1.1            parallel_4.0.4       sandwich_3.0-1      
 [64] RColorBrewer_1.1-2   yaml_2.2.1           curl_4.3.2           gridExtra_2.3        sass_0.4.0           gdtools_0.2.3        rpart_4.1-15        
 [71] latticeExtra_0.6-29  stringi_1.7.6        corrplot_0.84        nortest_1.0-4        e1071_1.7-9          checkmate_2.0.0      zip_2.1.1           
 [78] rlang_0.4.12         pkgconfig_2.0.3      systemfonts_1.0.1    evaluate_0.14        lattice_0.20-41      labeling_0.4.2       htmlwidgets_1.5.4   
 [85] bit_4.0.4            tidyselect_1.1.1     magrittr_2.0.1       R6_2.5.1             generics_0.1.1       Hmisc_4.6-0          DBI_1.1.0           
 [92] pillar_1.6.4         haven_2.4.3          foreign_0.8-81       withr_2.4.3          prettydoc_0.4.1      survival_3.2-13      abind_1.4-5         
 [99] nnet_7.3-15          modelr_0.1.8         crayon_1.4.2         car_3.0-10           utf8_1.2.2           tzdb_0.2.0           rmarkdown_2.11      
[106] jpeg_0.1-9           grid_4.0.4           readxl_1.3.1         data.table_1.14.2    webshot_0.5.2        reprex_0.3.0         digest_0.6.28       
[113] munsell_0.5.0        viridisLite_0.4.0    kableExtra_1.3.1     bslib_0.2.4 
