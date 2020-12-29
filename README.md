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
### III. Required R packages
1) DESeq2
2) ggplot2
3) pheatmap
4) vsn
5) plotly
6) RColorBrewer
7) distances
8) rmarkdown
