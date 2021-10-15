# GALC

In this project we studied role of GALC in Parkinson's disease

##GalCase activtiy GWAS##
-At the first step we performed GWAS on GalCase activtiy in two independent cohorts with further meta-analysis
-We then applied conditional and joint analyses (COJO) to identify independent SNPs in the GWASs after adjusting for the top hits
-Next, we repeated GWASs adjusting for top hits and  meta-analysed results from both cohorts using METAL package in R 
-Mirror Manhattan plots were created with the Hudson R package (https://github.com/anastasia-lucas/hudson)

#Colocolization analysis#

-Colocalization analysis between GALC GWAS and GTEx V7 summary statistics of selected brain regions (substantia nigra, frontal cortex) and blood QTL (https://www.ebi.ac.uk/eqtl/) was performed using the coloc R package (https://chr1swallace.github.io/coloc/index.html) 

#Mendelian randomization#

-Mendelian randomization was performed using GalCase GWAS from previous analysis as exposure and Parkinson's disease GWAS as outcome
##Analysis of rare variants was performed was perfromed as previously described##
