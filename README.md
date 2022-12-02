# Elasticity_curve_analysis
This repository contains the analysis portion of the code for the manuscript entitled: "Elasticity curves describe streamflow sensitivity to precipitation across the entire flow distribution", submitted to HESS in 2022. 

The associated markdown file includes subsections with relevant functions, calculation of elasticity curve data using single-site linear models, normalization of the curve data, clustering of curve data, calculation of elasticity curve data using panel regression models, and the use of a random forest model to select the best predictors of cluster membership.    

This is provided with a small subsample of the preprocessed data, thus the results will differ somewhat from those in the paper. 

Note: the delayedflow package is only available on github as of December 2, 2022: https://modche.github.io/delayedflow/

1. To run this script, download the associated files
2. The data contains: one preprocessed streamflow file containing daily flow percentile and climatological data adapted from PRISM: "processed_flow_sample.csv" and one file containing catchment attributes data: "mods.csv" which were compiled and processed separately. 
3. "knit" the document
