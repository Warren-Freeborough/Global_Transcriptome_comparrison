# Global_Transcriptome_comparrison
An automated R Script designed to quantify the similarity of processed global transcriptome data 

This script is designed to work on processed transcriptomic data containing the PFAM IDs of differenitally expressed genes

Dependancies 
Requires the following R packages and their dependancies:
1) heatmap.plus
2) gplots
3) RColorBrewer
4) glpots 
5) pheatmap
              
Input
It requires that the input data be in the csv format and placed in your working directrory in R. 
In order to work, the column containing the PFAM IDs should be appropriately named as "Pfam ID" and the expression of the genes should fall under the "Log2Fold" column

