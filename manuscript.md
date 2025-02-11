
# Working Title 
# Unravelling Bronchopulmonary Dysplasia Through Multi-Omics Meta-Analysis

<!-- To add a reference, add the PMID -->


## Introduction
### Problem and Question
Premature birth significantly increases the risk of both complications and long-term disabilities [1,2]. Bronchopulmonary dysplasia (BPD), also known as Chronic Lung Disease, is one of the most common complications of preterm birth affecting up to 30% of preterm infants born before 32 weeks gestational age (GA). The multifactorial nature of BPD makes characterisation difficult. Antenatal and postnatal factors disrupt the developing lung leading to decreased alveolarisation, larger alveoli, irregular pulmonary vessels, and fibrotic tissue [10,11]. In particular, the measures taken at birth to increase survival of preterm infants causes damage to the developing lungs by oxygen toxicity, pulmonary inflammation, and steroid-altered development [24213917]. The effects and consequences of BPD are only beginning to be understood but are life-long - individuals with BPD are more likely to require rehospitalisation during their childhood, to have limited lung function and to display delayed neurodevelopment, compared to VPTI without BPD [12-15]. [EXPAND]
There is an urgent need for effective treatments as 2000 new BPD cases occur each year in the UK [REF]

### Heterogeneity of BPD
[FILL IN]

### Genetics of BPD
The genetic contribution to BPD development remains unclear; unravelling this could aid in risk prediction, targeted therapies, and understanding disease mechanisms.  So far, no genes have been successfully associated with bronchopulmonary dysplasia in humans. Attempts to identify genes associated with the development of BPD via Genome Wide Association Studies (GWAS) and exome sequencing have had only moderate success; while some candidates have been identified [spock2] no gene has ever reached stringent significance levels.[23–27] 

### Animal Models and their suitability
Research often uses rodent models of BPD, exposing neonatal mice or rats to hyperoxia, mimicking lung injury.  A full-term human is born early in the alveolarization stage of lung development, with 150 million alveoli at birth, 50% of the expected adult number [3956418]. Rodents are born during the saccular stage with alveolarization beginning approximately 5 days after birth [914698]. A key difference is that rodent lungs are primed for gas exchange at this stage in development as the animal must survive ex utero [914698]. In contrast, human lungs are not designed for gas exchange in these earlier stages of development and require medical intervention, resulting in imapired alveolar development [27222921]. This brings into question the relevance of multi-omic research using rodent models aimed toward identifying potential therapeutic targets in BPD. To address this question, this study compares systematically collated information from both human and rodent studies.

### Results summary
To identify existing literature that could provide informative datasets indicating genes associated with BPD, we conducted a systematic review of published studies manuscripts pertaining to the disease. Results were extracted from identified studies, where possible, and analysed using MAIC. MAIC is a previously described algorithm that uses data-driven gene list weightings to produce a comprehensive ranked list of genes implicated in the disease or syndrome considered.[33339864;31919360;36094347] 

## Results

### Systematic review
We conducted a systematic review of existing studies, which reported associations between genes, transcripts, or proteins, and the development of BPD in humans or the study of BPD in animal (Supp inf). To ensure we were thorough in our approach and we did not limit the search to any specific definition of BPD in humans or animal models. Our search yielded 4450 unique citations that were evaluated for inclusion [Supplementary Figures for PRISMA diagrams]. For full text evaluation we retrieved XX articles for human studies and XX for animal studies. We found that although large animal models are often used to explore BPD,[examples, sheep IUGR, pig] we found no such study which met our inclusion criteria. [Supplementary figure of inclusion] 

[Anything else to  say here?]

### MAIC analysis
We first focused on the human studies and and identified 21 peer-reviewed studies that met our eligibility criteria. This yielded 31 gene lists, 23 ranked and 8 unranked, employing 5 experimental techniques (Mass spectrometry, GWAS, microarray, exomeSeq, RNAseq) [FIGURE]. The gene list could not be retrieved for one RNAseq study.  All but a single study used primary tissue or samples. While the definition of BPD varied between studies, over two-thirds of studies, (71.4%, 15/21), used respiratory support at 36 weeks GA.[NNAP/NICHD] 
Of 8017 genes implicated across the datasets. Only a single gene was supported by evidence from all 5 experimental techniques (RASGRP3). Few genes were supported by more than 1 method (n = 745, 9.74%), with 53 genes (0.6%) supported by >=3 methods. We prioritised 945 genes for further investigation, as previously described [Millar]. 

<!--We did not include miRNA lists.-->

### Functional Enrichment 
Functional enrichment analyses focused on the prioritised list of 945 genes. First, we performed over representation analysis. Genes associated with immunity, in particular T cell immunity, are over-represented. Reactome showed over representation of genes associated with the activity of ZAP-70 in T cell polarization and proliferation [PMID:12387734, 32948597, 15059847], though ZAP70 appears in the overall list of genes, it is not highly ranked by MAIC (3982) and is supported by a single study [yuon chou]. 

Next, we created a protein-protein interaction network. MCL clustering identified 32 clusters with >=5 members. Each of the 10 largest clusters contained >=10 members. Among these, we found programs associated with adaptive immunity, the SWI/SNF complex and post-translational protein phosphorylation. 

### Overlap with ARDS
We were interested in the similarities between ARDS in adults and BPD in neonates. We compared prioritised BPD genes to prioritised ARDS genes from our previous study [Millar]. We found that 112 genes were shared between the two datasets. Functional enrichment of analyses demonstrated that genes associated with T cell activity were enriched in this overlap. 

[TCELL RESPONSE?]

### Rodent - broad - systematic review info
<!-- Summary of rodent results -->

20 rodent BPD studies yielded 35 gene lists for analysis using MAIC (27 ranked and 8 unranked), employing 5 experimental techniques (GWAS, microarray, DNA methylation, RNAseq, scRNAseq) [FIGURE]. Of the 20 studies, 12 used mice models and 8 used rat models. The majority (16/20 80%) of these studies modeled BPD by exposing neonatal pups to hyperoxic environments. There was variation in the timeframe of hyperoxia and recovery and also the percent oxygen used for hyperoxia across the studies. Other methods to model BPD in rodent models included lipopolysaccharide (LPS) treatment (2 studies) and induced IUGR (2 studies). All but one included study used lung tissue for analyses. Of 6764 genes implicated across all datasets 3 genes were supported by evidence from all >=4 experimental techniques (RAC2, CXCR2, IL1R2). Few genes were supported by more than 1 method (n = 1209, 17.87%), with 94 genes (1.4%) supported by >=3 methods. We prioritised 1369 genes for further investigation.

### Rodent - specific - MAIC analysis
<!-- Specific results worth highlighting -->
GO biological processes (FDR 0.01). Top 50 enriched terms in bubble plot (figure)

Vasculature Development (GO:0001944), Angiogenesis (GO:0001568), Blood Vessel Morphogenesis (GO:0048514), and Blood Vessel Development (GO:0001525) were all among the top 50 significantly enriched terms. 

Programmed Cell Death, Apoptotic Process, Cell Death

Defense Response, Response to Cytokine, Response to stress

### Overlap between human and rodent




### Comparison to ARDS
The gene lists from MAIC were compared between BPD and ARDS, both of which are severe pulmonary conditions characterized by inflammation, tissue damage and impaired lung function. The ARDS MAIC ranked 7085 genes, with 1308 of these prioritised with the same methodology. ARDS and BPD gene lists were overlapped to identify genes within both subsets. There were 2054 genes that overlapped. The ARDS gene list was then overlapped with the BPD prioritised gene list. There were no genes found to be overlapped. The overlap found suggests that there are shared pathways and mechanisms involved in both conditions, likely due to the shared nature of their inflammatory processes, extracellular matrix remodeling and immune responses in lung injury. 

This lack of overlap in the prioritised group may be surprising, as there are shared clinical and pathological features of BPD and ARDS. However, while there may be common general processes (Figure 4a), the specific genes driving the most critical biological processes in these conditions may be distinct. This could imply that although inflammation and tissue remodeling are present in both diseases, the cell types and signalling pathways involved might be different, potentially reflecting age-related differences in lung development. This finding may have implications for the development of targeted therapies that are more appropriate for the age-specific pathogenesis of each condition. 

<!-- Summary of overlap -->

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
