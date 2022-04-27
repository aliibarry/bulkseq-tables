# Exploring the molecular underpinnings of neuropathic pain in primary afferent subtypes

<p>Allison Marie Barry <br>
Green Templeton College <br>
University of Oxford <br>
allimariebarry@gmail.com </p>

## Supplementary tables  
### Naive comparisions  
```
~ Population
~ Population + Sex
```
* DRGsubtype_Zheng2019-genesets.csv : 8 neuronal subtype genesets curated from Zheng et al 2019 (DOI: 10.1016/j.neuron.2019.05.039) [GSE131230][1]  
* DRGsubtype_geneenrichment.csv : Gene enrichment for each subtype in the current study, based on 75% confidence intervals  
* DRGsubtype_sex_DEG.xlsx : Differentially expressed genes (DEGs) for each subtype, with female reference  
* DRGsubtype_sex_DEGoverlap.csv : Overlap in DEGs across subtype  
* DRGsubtype_sex_GO.xlsx : GO term analyses using GoSeq (R) for each subtype  
* DRGsubtype_sex_GSEA.xlsx : GSEA analyses using ClusterProfiler (R) against all gene sets available from the Molecular Signatures Database (MSigDB). Samples were ranked by LFC. 


### General Injury signatures  
```
~ Time + Condition
```
* DRGsubtype_general-injury_DEG: 3D tab: Ipsilateral vs contralateral samples from 3 days post-SNI (an acute timepoint). 4W tab: Ipsilateral vs contralateral samples from 4 days post-SNI (a chronic timepoint). 4W v 3D tab: Comparison of ipsilateral samples across timepoints.Contains samples from all subtypes. P < 0.05, all LFC.  
* DRGsubtype_gneeral-injury_GSEA: GSEA analyses using ClusterProfiler (R) against all gene sets available from the Molecular Signatures Database (MSigDB). Samples were ranked by LFC.
* DRGsubtype_general-injury_GO: GO term analyses using GoSeq (R) for general comparisons

### Subtype Injury signatures  
```
~ Time + Condition + Population
```

[1]: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE131230 "GSE131230"

