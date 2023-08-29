`N202308291008` The pharmacoepigenomic landscape of cancer cell lines reveals the epigenetic component of drug sensitivity

 Key words: `human` `cancer` `epigenetic` `drug sensitivity`  `high-throughput drug screens (HTS)` `GDSC` `TCGA`
 
# Paper reading summary
## main idea
the paper analyse over 700 cancer cell line across 22 cancer type and 453 anti-cancer compounds to find methylation marker that sensitive to drugs

## background
1. using biomarker to classify patient, and make precise treatment and do prognostic analysis is helpful in increasing success rate of clinical trials.
2. hypermethylation on tumor suppressor genes and gene bodies can deregulate oncogenic pathway.
3. current biomarker stuies have focused on somatic mutation and copy number variations, DNA methylation markers are still sparse.
4. DNA methylation biomarker can be identified to predict drug response by method like machine learning.
5. finding DNA methylation that associated with drug response.
6. integrate genetic, epigentic, transcritomic and protein interaction data to try to interprete the mechnism between epigentic regulation and drug response.
   
## how to detect DNA methylation drug sensitive biomarker in the context of transcriptional and mutational pattern?
1. Identifying epigentic biomarkers of drug response; and filter out markers from a several standard, interms of expression, mutation, protein interaction, consistency with primary tumor data...
2. mainly focus on the association between drug response, gene expression and methylation status.
   
## method main point
1. datasource, cancer cell line from Genomics of Drug Sensitivity in Cancer (GDSC); primary tumor sample from The Cancer Genome Atlas (TCGA)
2. ways to deal with DNA methylation microarray data; Bioconductor package Minfi; BMIQ from ChAMP.

## inspired directions
1. creteria that used to select reliable epigenetic biomarker is quite reasonable and make sence to me.
2. think about how to link with comet and depmap database, the association between drug, gene expression and methylation on pediatric cancer type? at least can start from here.

# Reference
`Z:\ResearchHome\Groups\geelegrp\home\yzhang24\5_paper\s42003-023-05198-y`

# words
1. empowered; Epigenetic drug response biomarkers are empowered by studying DNA methylation and gene expression patterns; allow, permit.
