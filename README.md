## PRM analysis M.oryzae _Guy11_ vs _dpmk1_

This repo contains PRM analysis of _Magnaporthe oryzae_ strains _Guy11_ vs _dpmk1_.

## SL TICKETS

1499

## Info

Performed as described in the repo `.Rmd` using the tools previously developed in `pepdiff` [https://github.com/TeamMacLean/pepdiff](https://github.com/TeamMacLean/pepdiff).

## Lab Book

  * 6-12-2021
    Added `analysis/001_data_preparation.Rmd`, `analysis/002_data_checks.Rmd` and `analysis/003_da_estimates.Rmd`; generating results `analysis/003_differential_abundance_<sample>_estimates.xslx`.

 * 7-02-21
  Finalised replacement scheme and performed final da estimates. Performed k-means clustering analysis

  * 26-10-22 [CJ]
  GO enrichment analysis for each of the five clusters.

  * 01-12-22 [CJ]
  Add one heatmap showing selected targets (direct targets of pmk1) as annotation and one heatmap only displaying the selected targets; also add GO enrichement of the proteins corresponding to the selected targets. 
  
  * 15-12-22 [CJ]
  Qualitative comparison PRM and MS1 (based on visual trends).
  
  * 27-01-2023 [CJ]
  MS1 heatmap for select pathways.
  
  * 20-03-2023 [CJ]
  Barplots for selected peptides from the MS1 dataset. 
  
  ## TODO
  
  - [x] ~~Re-organise directories for input files and output files~~ >> project now contains directories for data, results, and graphics. 
