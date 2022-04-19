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
* DRGsubtype_sex_GSEA.xlsx : GSEA analyses using ClusterProfiler (R) against all gene sets available from the Molecular Signatures Database (MSigDB)   


### General Injury signatures  
```
~ Time + Condition
```
* INJURY-general_DEG_3D: Ipsilateral vs contralateral samples from 3 days post-SNI (an acute timepoint). Contains samples from all subtypes. Not filtered for LFC.  
* INJURY-general_DEG_4W: Ipsilateral vs contralateral samples from 3 days post-SNI (an acute timepoint). Contains samples from all subtypes. Not filtered for LFC.  
* INJURY-general_DEG_overlap: overlapping DEGs (LFC >1, FDR < 0.05) from DEG_3D and DEG_4W tables.  
* INJURY-general_DEG_4wv3D_ipsilateral: 4W ipsilateral vs 3D ipsilateral samples. 

### Subtype Injury signatures  
```
~ Time + Condition + Population
```

[1]: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE131230 "GSE131230"

