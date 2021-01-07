# Chernobyl Thyroid Cancer - Scores
## I. Description
Here are the R markdown files for generating the the BRAFV600E-RAS score (BRS),the thyroid differentiation score (TDS),and the ERK-activity score.
## II. Contents
1) [BRS_totalRNA_DE.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Scores/blob/main/BRS_totalRNA_DE.Rmd): Detection of differentially expressed genes between BRAFV600E and RAS samples (tumor-normal paired samples only) using DESeq2 
2) [BRS_totalRNA.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Scores/blob/main/BRS_totalRNA.Rmd): Estimating the degree to which the gene expression profiles resemble either BRAFV600Eor RAS-mutated PTC with the BRAFV600E – RAS score 
3) [BRS_TCGAgenes.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Scores/blob/main/BRS_TCGAgenes.Rmd): Estimating the degree to which the gene expression profiles resemble either BRAFV600Eor RAS-mutated PTC with the BRAFV600E – RAS score, using differentially expressed genes between BRAFV600E and RAS samples used in the TCGA analysis 
4) [BRS_miRNA_DE.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Scores/blob/main/BRS_miRNA_DE.Rmd): Detection of differentially expressed miRNAs between BRAFV600E and RAS samples (tumor-normal paired samples only) using DESeq2 
5) [BRS_miRNA.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Scores/blob/main/BRS_miRNA.Rmd): Estimating the degree to which the miRNA expression profiles resemble either BRAFV600Eor RAS-mutated PTC with the BRAFV600E – RAS score 
6) [BRS_meth.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Scores/blob/main/BRS_meth.Rmd): Estimating the degree to which the methylation profiles resemble either BRAFV600Eor RAS-mutated PTC with the BRAFV600E – RAS score 
7) [TDS.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Scores/blob/main/TDS.Rmd): Generating the thyroid differentiation score (TDS), based on expression of 16 thyroid metabolism andfunction genes
8) [ERK.Rmd](https://github.com/NCI-CGR/ChernobylThyroidCancer-Scores/blob/main/ERK.Rmd): Generating the ERK-activity score of 52 expressed genes responsive to MEK inhibition
### III. Required R packages
* [DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html)
* [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html)
* [pheatmap](https://cran.r-project.org/web/packages/pheatmap/index.html)
* [vsn](https://www.bioconductor.org/packages/release/bioc/html/vsn.html)
* [plotly](https://cran.r-project.org/web/packages/plotly/index.html)
* [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html)
* [distances](https://cran.r-project.org/web/packages/distances/index.html)
* [rmarkdown](https://cran.r-project.org/web/packages/rmarkdown/index.html)
* [data.table](https://cran.r-project.org/web/packages/data.table/index.html)
* [matrixStats](https://cran.rstudio.com/web/packages/matrixStats/index.html)
