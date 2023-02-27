#  Single cell analysis of the effects of developmental lead (Pb) exposure on the mouse hippocampus

## Citation Information
Bakulski KM, Dou JF, Thompson RT, Lee C, Middleton LY, Bambarendage PUP, Ferris SP, Jones TR, Neier K, Zhou X, Sartor MA, Hammoud SS, Dolinoy DC, Colacino JA. 2020. Single cell analysis of the effects of developmental lead (Pb) exposure on the mouse hippocampus. Toxicological Sciences. PMID: 32458983. PMCID: PMC7416319. DOI: 10.1093/toxsci/kfaa069

This Github repository contains the data management and analytic scripts to produce the following manuscript:[Single-Cell Analysis of the Gene Expression Effects of Developmental Lead (Pb) Exposure on the Mouse Hippocampus](https://pubmed.ncbi.nlm.nih.gov/32458983/)

## Abstract
Lead (Pb) exposure is ubiquitous with permanent neurodevelopmental effects. The hippocampus brain region is involved in learning and memory with heterogeneous cellular composition. The hippocampus cell type-specific responses to Pb are unknown. The objective of this study is to examine perinatal Pb treatment effects on adult hippocampus gene expression, at the level of individual cells. In mice perinatally exposed to control water or a human physiologically relevant level (32 ppm in maternal drinking water) of Pb, 2 weeks prior to mating through weaning, we tested for hippocampus gene expression and cellular differences at 5 months of age. We sequenced RNA from 5258 hippocampal cells to (1) test for treatment gene expression differences averaged across all cells, (2) compare cell cluster composition by treatment, and (3) test for treatment gene expression and pathway differences within cell clusters. Gene expression patterns revealed 12 hippocampus cell clusters, mapping to major expected cell types (eg, microglia, astrocytes, neurons, and oligodendrocytes). Perinatal Pb treatment was associated with 12.4% more oligodendrocytes (p = 4.4 × 10-21) in adult mice. Across all cells, Pb treatment was associated with expression of cell cluster marker genes. Within cell clusters, Pb treatment (q < 0.05) caused differential gene expression in endothelial, microglial, pericyte, and astrocyte cells. Pb treatment upregulated protein folding pathways in microglia (p = 3.4 × 10-9) and stress response in oligodendrocytes (p = 3.2 × 10-5). Bulk tissue analysis may be influenced by changes in cell type composition, obscuring effects within vulnerable cell types. This study serves as a biological reference for future single-cell toxicant studies, to ultimately characterize molecular effects on cognition and behavior.

## Funding
NIEHS TaRGET II Consortium award to the University of Michigan (U01 ES026697) for the mouse exposure study; NIEHS Michigan Center on Lifestage Environmental Exposures and Disease (M-LEEaD; P30 ES017885) for the sequencing experiment; NIH (grants R01 ES025531, R01 ES025574, R01 AG055406, R01 MD013299, UG3 OD023285, UH3 OD023285, and P30 AG053760 to J.F.D. and K.M.B.); NIH (R01 ES028802 and UL1TR002240 to J.A.C.); NIEHS (T32 ES007062 to B.P.U.P.); NIEHS (T32 ES007062 to K.N.); and NICHD (T32 HD079342 to K.N.)

## Data availability
Sequencing data are available on the Gene Expression Omnibus (GEO at https://www.ncbi.nlm.nih.gov/geo/ with accession number pending). Code to produce all R analyses in this manuscript is available (https://github.com/bakulskilab).

## Script Files
*Scripts* folder contains the codes to produce all analysis

Pb_Hippocampus_PowerSupplement.Rmd: analysis on power simulation

clustering.Rmd: code on single Cell RNAseq Clustering

differential_gene_expression.Rmd: code on differential expression analysis
