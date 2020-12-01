## Microbiota-of-estrildid-finches-

Analysis of microbiome data on R for the project :

"The Gut Microbial Composition is Species-specific and Individual-specific in two Species of Estrildid Finches, the Bengalese Finch and the Zebra Finch"

Authors:

Öncü Maraci, Anna Antonatou-Papaioannou Sebastian Jünneman, Omar Castillo-Gutiérrez, Tobias Busche, Jörn Kalinowski, Barbara A. Caspers








## Detailed SessionInfo in R

sessionInfo()
R version 4.0.2 (2020-06-22)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows >= 8 x64 (build 9200)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.1252  LC_CTYPE=English_United States.1252    LC_MONETARY=English_United States.1252
[4] LC_NUMERIC=C                           LC_TIME=English_United States.1252    
system code page: 65001

attached base packages:
 [1] stats4    grid      parallel  stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] rfm_0.2.2                   DESeq2_1.28.1               SummarizedExperiment_1.18.1 DelayedArray_0.14.1        
 [5] matrixStats_0.56.0          GenomicRanges_1.40.0        GenomeInfoDb_1.24.2         IRanges_2.22.2             
 [9] S4Vectors_0.26.1            microbiome_1.10.0           biomformat_1.16.0           phyloseq_1.32.0            
[13] reshape2_1.4.4              scales_1.1.1                dplyr_1.0.2                 ggpubr_0.4.0               
[17] ggplot2_3.3.2               rstatix_0.6.0               dunn.test_1.3.5             picante_1.8.2              
[21] nlme_3.1-148                vegan_2.5-6                 lattice_0.20-41             permute_0.9-5              
[25] ape_5.4-1                   metagenomeSeq_1.30.0        RColorBrewer_1.1-2          glmnet_4.0-2               
[29] Matrix_1.2-18               limma_3.44.3                Biobase_2.48.0              BiocGenerics_0.34.0        

loaded via a namespace (and not attached):
  [1] Rtsne_0.15             colorspace_1.4-1       ggsignif_0.6.0         ellipsis_0.3.1         rio_0.5.16            
  [6] rprojroot_1.3-2        XVector_0.28.0         fs_1.5.0               rstudioapi_0.11        remotes_2.2.0         
 [11] bit64_4.0.5            AnnotationDbi_1.50.3   fansi_0.4.1            codetools_0.2-16       splines_4.0.2         
 [16] geneplotter_1.66.0     pkgload_1.1.0          ade4_1.7-15            jsonlite_1.6.1         broom_0.7.0           
 [21] annotate_1.66.0        cluster_2.1.0          compiler_4.0.2         backports_1.1.9        assertthat_0.2.1      
 [26] cli_2.0.2              prettyunits_1.1.1      tools_4.0.2            igraph_1.2.5           gtable_0.3.0          
 [31] glue_1.4.2             GenomeInfoDbData_1.2.3 Rcpp_1.0.5             carData_3.0-4          cellranger_1.1.0      
 [36] vctrs_0.3.2            Biostrings_2.56.0      multtest_2.44.0        gdata_2.18.0           iterators_1.0.12      
 [41] stringr_1.4.0          ps_1.3.4               testthat_2.3.2         openxlsx_4.1.5         lifecycle_0.2.0       
 [46] devtools_2.3.1         gtools_3.8.2           XML_3.99-0.3           zlibbioc_1.34.0        MASS_7.3-51.6         
 [51] hms_0.5.3              rhdf5_2.32.0           yaml_2.2.1             curl_4.3               memoise_1.1.0         
 [56] stringi_1.5.3          RSQLite_2.2.0          genefilter_1.70.0      desc_1.2.0             foreach_1.5.0         
 [61] caTools_1.18.0         pkgbuild_1.1.0         zip_2.0.4              BiocParallel_1.22.0    shape_1.4.4           
 [66] rlang_0.4.7            pkgconfig_2.0.3        bitops_1.0-6           Wrench_1.6.0           purrr_0.3.4           
 [71] Rhdf5lib_1.10.0        processx_3.4.4         cowplot_1.1.0          bit_4.0.4              tidyselect_1.1.0      
 [76] plyr_1.8.6             magrittr_1.5           R6_2.4.1               gplots_3.0.4           generics_0.0.2        
 [81] DBI_1.1.0              withr_2.2.0            pillar_1.4.6           haven_2.3.1            foreign_0.8-80        
 [86] mgcv_1.8-31            survival_3.1-12        abind_1.4-5            RCurl_1.98-1.2         tibble_3.0.1          
 [91] crayon_1.3.4           car_3.0-9              KernSmooth_2.23-17     usethis_1.6.1          locfit_1.5-9.4        
 [96] readxl_1.3.1           data.table_1.13.0      callr_3.4.4            blob_1.2.1             forcats_0.5.0         
[101] digest_0.6.25          xtable_1.8-4           tidyr_1.1.0            munsell_0.5.0          sessioninfo_1.1.1   
