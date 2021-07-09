# Mcl-1
RNAseq analysis of 'EGF-mediated induction of Mcl-1 at the switch to lactation is essential for alveolar cell survival.'

Open 01 Rmd file to begin analysis; this merges initial gene counts and sample txt files into a DGEList object, y, that can be normalized and edited to include gene annotations. 

*GOAL 1)* Convert txt data into a DGEList object (y) that contains gene annotation data. *GOAL 2)* Filter low gene counts, normalize compositional count data to cpm. *GOAL 3)* Describe existing variation. Hint: library size affects calcNormFactors, use TMM and a before/after MDS or PCA plot.

Open 02 Rmd file to load day1analysis; 
*GOAL 1)* Fix compositional bias using voom & limma (v).
