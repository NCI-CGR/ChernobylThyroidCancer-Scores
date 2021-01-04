# Chernobyl Thyroid Cancer - Scores
## I. Description
Here are the Rmarkdown files for generating the the BRAFV600E-RAS score (BRS),the thyroid differentiation score (TDS),and the ERK-activity score.
## II. Contents
1) BRS_totalRNA_DE.Rmd: Detection of differentially expressed genes between BRAFV600E and RAS samples (tumor-normal paired samples only) using DESeq2 
2) BRS_totalRNA.Rmd: Estimating the degree to which the gene expression profiles resemble either BRAFV600Eor RAS-mutated PTC with the BRAFV600E – RAS score 
3) BRS_TCGAgenes.Rmd: Estimating the degree to which the gene expression profiles resemble either BRAFV600Eor RAS-mutated PTC with the BRAFV600E – RAS score, using differentially expressed genes between BRAFV600E and RAS samples used in the TCGA analysis 
4) BRS_miRNA_DE.Rmd: Detection of differentially expressed miRNAs between BRAFV600E and RAS samples (tumor-normal paired samples only) using DESeq2 
5) BRS_miRNA.Rmd: Estimating the degree to which the miRNA expression profiles resemble either BRAFV600Eor RAS-mutated PTC with the BRAFV600E – RAS score 
6) BRS_meth.Rmd: Estimating the degree to which the methylation profiles resemble either BRAFV600Eor RAS-mutated PTC with the BRAFV600E – RAS score 
7) TDS.Rmd: Generating the thyroid differentiation score (TDS), based on expression of 16 thyroid metabolism andfunction genes
8) ERK.Rmd: Generating the ERK-activity score of 52 expressed genes responsive to MEK inhibition
### III. Required R packages
1) [DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html)
2) [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html)
3) [pheatmap](https://cran.r-project.org/web/packages/pheatmap/index.html)
4) [vsn](https://www.bioconductor.org/packages/release/bioc/html/vsn.html)
5) [plotly](https://cran.r-project.org/web/packages/plotly/index.html)
6) [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html)
7) [distances](https://cran.r-project.org/web/packages/distances/index.html)
8) [rmarkdown](https://cran.r-project.org/web/packages/rmarkdown/index.html)
9) [data.table](https://cran.r-project.org/web/packages/data.table/index.html)
10) [matrixStats](https://cran.rstudio.com/web/packages/matrixStats/index.html)
