Here we calculate miRNA stability across three types of samples:
1. Pre-Radiotherapy samples
2. Post-Radiotherapy samples
3. Healthy samples

Info about each sample are contained in the *SampleType.csv* file 

miRNA stability is measure using the **geNorm** function of the R package **ctrlGene**

## geNorm
For more information, see this [article](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC126239/)

Here an abstract of the article:
> we developed a gene-stability measure to determine the expression stability of control genes on the basis of non-normalized expression levels. This measure relies on the principle that the expression ratio of two ideal internal control genes is identical in all samples, regardless of the experimental condition or cell type. In this way, variation of the expression ratios of two real-life housekeeping genes reflects the fact that one (or both) of the genes is (are) not constantly expressed, with increasing variation in ratio corresponding to decreasing expression stability. For every control gene we determined the pairwise variation with all other control genes as the standard deviation of the logarithmically transformed expression ratios, and defined the internal control gene-stability measure M as the average pairwise variation of a particular gene with all other control genes. Genes with the lowest M values have the most stable expression. Assuming that the control genes are not co-regulated, stepwise exclusion of the gene with the highest M value results in a combination of two constitutively expressed housekeeping genes that have the most stable expression in the tested samples.
