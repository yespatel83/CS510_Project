## Study Aim

The aim of the script below is to run genetic analyses (a mini GWAS) to identify genetic variants that are associated with breast cancer risk. Particularly we are looking at a sample of 3,135 genetic variants among ~100K European individuals from around the world who were enrolled in this study from various study cites. The output of the analyses will be a tab delimited .txt file with test statistics as well as Manhattan and Q-Q plots which will display our results to see if any markers are found to be significantly associated across the genome.

## Data (Restricted by IRB)

The data used in the analyses is confidential and cannot be shared due to IRB restrictions and thus not allowed to be posted on GitHub. You won't be able to run the code but it might help to reference that the data is a subset of the Breast Cancer Association Consortium detailed here: http://bcac.ccge.medschl.cam.ac.uk/

There are R Markdown .html files provided which allow you to see the structure and sample of the datasets, along with outputs of the code - the .html files eseentially walk you through the code/script to produces the outputs and results.

The following data files (restricted by IRB) were used and will be referenced in the analyses and scripts below:

1) BCAC_582_imputed_dosages.txt,
2) BCAC_582_pheno_yp.txt,
3) BCAC_582_sample_order.txt,
4) BCAC_582_imputed_variants_info.txt

## Output Files

The following output files were created by the script and have been provided in the above "Outputs" directory:

1) The script will output the complete results: BCAC_Overall_Status_Results.txt
2) Manhattan Plot: MH_plot.tiff
3) Quantile-Quantile Plot: QQ_plot.tiff
4) A truncated version of the results: BCAC_Overall_Status_Results_top_hits.txt

## How to run the code
This code is NOT executable due to data IRB restrictions. The R-Markdown .html files include the code, data views, and outputs. The .html files are in the "R_Markdown" directory above, please use the version titled "CS510_Project_Final.html" for the review.

Likewise, the code that produced the .html file above can be found in the "R_Code" directory, please use the version titled "CS510_Project_Final.Rmd" for the review.

