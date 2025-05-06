
# Working Title 
# Unravelling Bronchopulmonary Dysplasia Through Multi-Omics Meta-Analysis

<!-- To add a reference, add the PMID -->


## Introduction
### Background

Bronchopulmonary dysplasia (BPD), also known as Chronic Lung Disease, is one of the most common complications of preterm birth, affecting up to 30% of preterm infants born before 32 weeks post-menstrual age (PMA).1,2,3 Antenatal and postnatal factors disrupt the developing lung leading to decreased alveolarisation, larger alveoli, irregular pulmonary vessels, and fibrotic tissue.4,5 The effects of BPD are life-long; individuals with BPD are more likely to require rehospitalisation during their childhood, to have limited lung function and to display delayed neurodevelopment, compared to those born preterm without BPD.6–9

Understanding the molecular mechanisms that contribute to BPD could aid in risk prediction, targeted therapies, and understanding disease mechanisms. The heterogeneity of the disease has hampered efforts to identify reliable, consistent biomarkers. So far, though some candidates have been identified (e.g. SPOCK2, CRP) no gene has been significantly associated with the development of BPD via Genome Wide Association Studies (GWAS) or exome sequencing.10–14 This is despite indications from twin studies of the heritability of BPD.15,16 Transcriptomic data has been used to identify four endotypes of BPD, distinguished by T helper cell and T cell signalling.17  Together these, and other studies, reflect an effort to incorporate insights from genome-scale research, complementing the longstanding emphasis on clinical studies in the field.

Animal models, particularly murine moodels, have been used extensively to investgiate the pathophysiology of BPD. The majority of this work has focussed on hyperoxia-induced lung injury, aiming to replicate the disrupted alveolarisation and inflammation seen in pre-term infants. Comparative transcriptomic analysis between species has the potential to help distinguish universal disease mechanisms from species specific responses. However, due to developmental differences in human and rodent lungs, these pathways may not be directly comparable."

Integrating results from heterogenous sources can allow for novel insights. We conducted a systematic review of the BPD literature, focusing on genome-scale studies in humans and rodents. Results were extracted from identified studies, where possible, and analysed using MAIC. MAIC is a previously described algorithm that uses data-driven gene list weightings to produce a comprehensive ranked list of genes associated with the trait of interest.18–20

Our findings demonstrate that BPD is a complex disease which involves dysregulation in immune signaling, vascular development and extracellular matrix organisation. Of note, several of our analyses highlighted the involvement of T cell-associated genes, suggesting that adaptive immunity may play a larger role in BPD pathogenesis than previously appreciated.

 
## Results

### Systematic review and meta-analysis by information content
We conducted a systematic review of studies that reported associations between genes, transcripts, or proteins, and the development of BPD in humans or the study of BPD in animal models. We did not limit the search to any specific definition of BPD in humans or animal models. Our search yielded 4450 unique citations that were evaluated for inclusion [Supplementary Figures 1 and 2]. For full text evaluation we retrieved 76 articles for human studies and 118 for animal studies. There was no overlap. Although large animal models are occasionally used to explore BPD,2122 we found none that met our inclusion criteria which are outlined in Supplementary Table 2 and 3. 

From the 81 human studies, 21 met our eligibility criteria. This yielded 31 gene lists, 23 ranked and 8 unranked, employing 5 experimental techniques (Mass spectrometry, GWAS, microarray, exomeSeq, RNAseq) [Supplementary Table 3] and representing 4358 infants (cases = 2247, controls = 2111).  All but a single study used primary tissue. While the definition of BPD varied between studies, over two-thirds of studies, (71.4%, 15/21), used receipt of respiratory support at 36 weeks PMA.3 Of 8017 unique genes collated across the datasets, only a single gene was supported by evidence from all 5 experimental techniques (RASGRP3, rank = 1). Few genes were supported by more than 1 method (n = 745, 9.74%), with 53 genes (0.6%) supported by >=3 methods. We prioritised 945 genes for further investigation, as previously described [Figure 1A].23

<!--We did not include miRNA lists.-->

### Tissue and Cell-Specific Expression


### Functional Enrichment 
Functional enrichment analyses focused on the prioritised list of 945 genes. First, we performed over representation analysis. Genes associated with immunity, in particular T cell immunity, are over-represented. Reactome showed over representation of genes associated with the activity of ZAP-70 in T cell polarization and proliferation [PMID:12387734, 32948597, 15059847], though ZAP70 appears in the overall list of genes, it is not highly ranked by MAIC (3982) and is supported by a single study [yuon chou]. 

Next, we created a protein-protein interaction network. MCL clustering identified 32 clusters with >=5 members. Each of the 10 largest clusters contained >=10 members. Among these, we found programs associated with adaptive immunity, the SWI/SNF complex and post-translational protein phosphorylation. 

### Overlap with ARDS
We were interested in the similarities between ARDS in adults and BPD in neonates. both of which are severe pulmonary conditions characterized by inflammation, tissue damage and impaired lung function. The ARDS MAIC ranked 7085 genes, with 1308 of these prioritised with the same methodology.[Millar] We found that 112 genes were shared between the two prioritised datasets. Functional enrichment of analyses demonstrated that genes associated with T cell activity were enriched in this overlap. The overlap found suggests that there are shared pathways and mechanisms involved in both conditions, likely due to the shared nature of their inflammatory processes, extracellular matrix remodeling and immune responses in lung injury. This finding may have implications for the development of targeted therapies that are more appropriate for the age-specific pathogenesis of each condition. 

[TCELL RESPONSE?]

### Rodent - broad - systematic review info
20 rodent BPD studies yielded 35 gene lists for analysis using MAIC (27 ranked and 8 unranked), employing 5 experimental techniques (GWAS, microarray, DNA methylation, RNAseq, scRNAseq) [FIGURE]. Of the 20 studies, 12 used mice models and 8 used rat models. The majority (16/20 80%) of these studies modeled BPD by exposing neonatal pups to hyperoxic environments. There was variation in the timeframe of hyperoxia and recovery and also the percent oxygen used for hyperoxia across the studies. Other methods to model BPD in rodent models included lipopolysaccharide (LPS) treatment (2 studies) and induced IUGR (2 studies). All but one included study used lung tissue for analyses. Of 6764 genes implicated across all datasets 3 genes were supported by evidence from all >=4 experimental techniques (RAC2, CXCR2, IL1R2). Few genes were supported by more than 1 method (n = 1209, 17.87%), with 94 genes (1.4%) supported by >=3 methods. We prioritised 1369 genes for further investigation.

### Rodent - specific - MAIC analysis
<!-- Specific results worth highlighting -->
Our analysis prioritised 1783 genes for functional enrichment using the unit invariant knee method. These genes were further investigated using KEGG, Reactome and GO Biological Processes. From this, key themes emerged that supported evidence that BPD involves chronic inflammation, disrupted lung development and immune response. 

### Rodent - specific - Functional Enrichment
KEGG: Enriched terms supported evidence of dysregulated growth and development pathways including  ‘pathways in cancer’ and ‘transcriptional misregulation in cancer’. Alongside this, the ‘AGE-RAGE signalling pathway’ is associated with inflammation and oxidative stress – relating to hyperoxia induced injury in BPD. Enrichment of ‘complement and coagulation cascades’ points towards innate immune activity and potential vascular involvement. ‘Chemokine signalling’ and ‘TNF signalling’ emphasise the role of inflammatory processes.

Reactome: ‘Extracellular matrix (ECM) organisation’ alongside ‘collagen formation’ and ‘assembly of collagen fibrils’ highlights structural remodelling in BPD, reflecting fibrosis and impaired alveolarisation. ‘Elastic fibre formation’ may contribute to long-term respiratory dysfunction. Enrichment with reactome reinforced a strong inflammatory component observed in BPD (‘immune system’ and ‘innate immune system’). ‘Haemostasis’ and ‘platelet activation, signalling and aggregation’ indicate endothelial injury and pro-thrombotic processes within the lung vasculature. This, as well as ‘cell surface interactions at the vascular wall’ support evidence of vascular remodelling as a key factor in BPD pathophysiology. 

GOBP: Neutrophil-related processes were predominantly enriched, including: ‘neutrophil-mediated immunity’, ‘Neutrophil activation involved in immune response’, and ‘neutrophil degranulation’. These terms highlight the role of innate immune cells and their inflammatory effects in BPD pathogenesis. Supporting results from the Reactome enrichment, ‘extracellular matrix organisation’ was significantly enriched, a hallmark of lung injury and fibrosis. Cytokine-related signalling was also enriched, particularly ‘cellular response to cytokine stimulus’ and ‘cytokine-mediated signalling pathway’. Apoptotic processes appeared both positively and negatively regulated, inferring complicated regulation of cell death during lung injury and repair. 

### Overlap between Human and Rodent BPD 
We analysed the overlap between the Human and rodent BPD MAIC results. Of the 8017 genes from the human results, and 7636 genes from the rodent results: 2747 genes overlapped (35.97%). Using the prioritised lists from both analyses, 945 human and 1783 rodent, there were 163 overlapping genes (9.14%). This relatively limited overlap may reflect species-specific differences in disease mechanisms, limiting the extent to which findings from rodent models can be directly translated to human BPD.

<!--the 163 number is 9.14% of the rodent list, but is 17.25% of the human list-->

We carried out functional enrichment of the overlapping prioritised genes using GOBP, KEGG and Reactome to investigate the biological mechanisms that may be conserved between species. Generally, this revealed a consistent signature of immune-related biological processes. (figures)

GOBP: Terms such as ‘neutrophil activation’, ‘neutrophil degranulation’, and ‘neutrophil-mediated immunity’ were significantly enriched, indicating a conserved involvement of neutrophil-driven innate immune responses in BPD pathogenesis across species. In addition, several terms relating to cytokine signalling and immune regulation were enriched, including ‘cytokine-mediated signalling pathway’, ‘cellular response to cytokine stimulus’, and ‘regulation of interleukin-2 biosynthetic process’. These results are in keeping with a shared up-regulation of both pro-inflammatory signalling and adaptive immune processes.

KEGG: Key pathways included ‘haematopoietic cell lineage’, ‘T cell receptor signalling’, and ‘cytokine–cytokine receptor interaction’, further support shared involvement of both innate and adaptive immune responses. Enrichment for ‘primary immunodeficiency genes’ and ‘cell adhesion molecules’ suggests dysregulation of immune development. Pathways such as ‘complement and coagulation cascades’, and those associated with infectious disease responses (Staphylococcus Aureus and Measles), reflect heightened inflammatory signalling.

Reactome: Enriched terms included broad categories such as ‘Immune System’ and ‘Adaptive Immune System’, as well as more specific pathways like ‘Cytokine Signalling in Immune System’ and ‘Signalling by Interleukins’, strengthen evidence of immune-mediated mechanisms. Several T cell-specific pathways were also enriched, including ‘Translocation of ZAP-70 to the Immunological Synapse’, ‘Phosphorylation of CD3 and TCR zeta chains’, and Costimulation by the CD28 family’, reinforcing the role of adaptive immunity. 

These findings suggest that despite broader transcriptomic differences between human and rodent BPD…

However due to developmental differences, these results may not be directly comparable...

## Discussion

## Methods

Systematic review and meta-analysis protocol was registered with the International Prospective Register of Systematic Reviews (PROSPERO – Human Code + CRD42024550657). 

### Search Strategy and Selection Criteria
#### Human
#### Animal
_•	Search Strategy – SUPP 
•	Inclusion and Exclusion criteria – SUPP__
A detailed description of our search strategy and eligibility criteria is provided in the supplementary materials. MEDLINE and Embase were searched on 24/05/2024. We included genome-wide studies reporting associations between genes, transcripts or proteins and BPD in both human and rodent models. For rodent studies, definitions of BPD study groups were accepted as hyperoxic exposure and induced low birth weight. We excluded in-vitro BPD models, and candidate studies (<50 genes/proteins). 

#### Study Selection and Data Extraction
Following deduplication, titles were initially screened using Screenatron (REF). This included organising the studies into separate collections of human and animal studies. Abstracts were then screened against eligibility criteria, with an independent author resolving inconsistencies. Full texts were retrieved and analysed for inclusion before extraction of gene lists for inclusion in MAIC. 

The human data was standardised according to HGNC symbols or Ensembl/RefSeq equivalents when no HGNC symbol was available. 
Animal data was mapped to human ortholog symbols to allow for comparison with the human MAIC results. 

#### MAIC
The MAIC algorithm has previously been described in detail (REF). A full description and the source code is available at https://baillielab.net/maic. MAIC combines both ranked and unranked lists, of unknown quality, to build a comprehensive ranked list of entities according to 4 basic assumptions. 
1.	There is a set of true positives (host genes implicated in BPD) 
2.	A gene is more likely to be a true positive if it appears in datasets from more than one source
3.	A gene is more likely to be a true positive if it appears in datasets with a higher proportion of replicated genes
4.	A gene is more likely to be a true positive if it appears in datasets from multiple methods or modalities.
