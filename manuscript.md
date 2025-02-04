
# Working Title 
# Unravelling Bronchopulmonary Dysplasia Through Multi-Omics Meta-Analysis

<!-- To add a reference, add the PMID -->


## Introduction


### Problem and Question

Premature birth significantly increases the risk of both complications and long-term disabilities [1,2].  Survival of infants following pre-term birth has dramatically improved in the past few decades [3]. Interventions include steroids, mechano-ventilation, and surfactant therapy to facilitate gas exchange in the lungs. While successful in enabling survival, these treatments can lead to Bronchopulmonary Dysplasia.  Bronchopulmonary Dysplasia (BPD) affects 30% of preterm infants born before 32 weeks gestational age and is partly due to the ventilatory interventions used to sustain life [3,4,5] The lungs are damaged by oxygen toxicity, pulmonary inflammation, and steroid-altered development [24213917]. The effects and consequences of BPD are only beginning to be understood but are life-long - individuals with BPD are more likely to require rehospitalisation during their childhood, to have limited lung function and to display delayed neurodevelopment, compared to VPTI without BPD [12-15]. There is an urgent need for effective treatments as 2000 new BPD cases occur each year in the UK [REF]

Which genes are prioritised as being implicated in development of BPD in humans and in animal models.

### Heterogeneity of BPD

- Genetics in disease.
  
### Importance of BPD
There were over 7000 very preterm infants (VPTI) in 2021 across the UK[6] and around 30% of these infants were on respiratory support at 36 weeks GA, indicating bronchopulmonary dysplasia according to the National Neonatal Audit Programme diagnostic criteria.[6,7,8] Bronchopulmonary dysplasia (BPD), also known as Chronic Lung Disease, is one of the most common complications of preterm birth and is increasing in prevalence most likely due to the increased survival rates of VPTI.[9,10] Antenatal and postnatal factors disrupt the developing lung leading to decreased alveolarisation, irregular pulmonary vessels, and fibrotic tissue [10,11].

The genetic contribution to BPD development remains unclear; unravelling this could aid in risk prediction, targeted therapies, and understanding disease mechanisms. So far, no genes have been successfully associated with bronchopulmonary dysplasia but implicated pathways include:



### State of the art

- Current potential mediators of BPD.

There is conflicting evidence for a heritable component of BPD [20–22] and attempts to identify genes via Genome Wide Association Studies (GWAS) and exome sequencing have had only moderate success; no gene has ever reached stringent significance levels.[23–27] So far, no genes have been successfully associated with bronchopulmonary dysplasia in humans.

### Animal Models and their suitability
Research often uses rodent models of BPD, exposing neonatal mice or rats to hyperoxia, mimicking lung injury. This approach effectively captures aspects of inflammation and oxidative stress but may not fully replicate the multifactorial nature of BPD. A full-term human is born early in the alveolarization stage of lung development, with 150 million alveoli at birth, 50% of the expected adult number [3956418]. Rodents are born during the saccular stage with alveolarization beginning approximately 5 days after birth [914698]. A key difference is that rodent lungs are primed for gas exchange at this stage in development as the animal must survive outside of the womb [914698]. In contrast, human lungs are not designed for gas exchange in these earlier stages of development and require medical intervention, resulting in less successful alveolar development [27222921]. This brings into question the relevance of multi-omic research using rodent models aimed toward identifying potential therapeutic targets in BPD. To address this question, this study compares systematically collated information from both human and rodent studies.

### Results summary
To identify existing literature that could provide informative datasets indicating genes associated with BPD, we conducted a systematic review of published studies manuscripts pertaining to the disease. Results were extracted from identified studies, where possible, and analysed using MAIC. MAIC is a previously described algorithm that uses data-driven gene list weightings to produce a comprehensive ranked list of genes implicated in the disease considered.[33339864;31919360;36094347] 

## Results

### Definition of BPD in humans and lack of large animal models  

We first conducted a systematic review of existing studies, which reported associations between genes, transcripts, or proteins, and the development of BPD in humans or the study of BPD in animal. Our search yielded 4450 unique citations that were evaluated for inclusion [Supplementary Figures for PRISMA diagrams]. 
<!-- What did we class as BPD and how wide did we cast the net -->
<!-- PRISMA supplementary for both human and animal -->
<!-- figure showing number of articles per animal in review-->

### Human - broad - systematic review info
We identified 24 studies in humans that met our eligibility criteria, all peer-reviewed. This yielded 32 gene lists, 22 ranked and 10 unranked employing 5 experimental techniques [FIGURE]. While the definition of BPD varied between studies, over half of studies, 63%, used some form of respiratory support at 36 weeks GA.  Data could not be retrieved for one study. Of 6844 genes implicated across these datasets, __950 were supported by evidence from more than one source__.  
<!-- Summary of human results -->

### Human - specific - MAIC analysis
Functional enrichment analysis of the 1055 prioritised genes identified by MAIC score was performed against the GO Biological Process database, resulting in 25 significantly enriched biological processes with a false discovery rate (FDR) ≤ 0.01. In particular, inflammatory, immune regulatory and cell proliferation pathways stood out (Figure 2). Platelet degranulation (GO:0002576) was found to be the most significantly enriched process, involving genes such as PDGFA, VEGFB, and THBS1, which encode for platelet-derived factors, in BPD pathogenesis. Dysregulated platelet activation in preterm infants can enhance local inflammation and disrupt normal vascularisation, contributing to impaired alveolarisation of the lungs. Platelets may therefore be implicated not only in hemostasis but also inflammatory signaling and tissue remodeling, which are both processes critical to BPD pathogenesis.

Negative regulation of endopeptidase activity (GO:0010951) and regulation of immune effector processes (GO:0002697) were also both significantly enriched, which further supports the idea of chronic inflammatory processes in BPD pathogenesis. In particular, these processes involved genes responsible for protease inhibition, such as SERPINA1 and SERPING1, which indicates the importance of maintaining the protease-antiprotease balance in the body to prevent lung injury and extracellular matrix degradation. Also, immune effector regulation, involving genes such as CR1, C1QB, and HLA-DRA, points to overactivation of the complement system and immune responses, which are known contributors to alveolar damage. Finally the enrichment of regulation of cell population proliferation (GO:0042127) suggests potential defects in lung cell proliferation, with genes such as FGF2 and TIMP1, may play a role in abnormal lung tissue repair. These findings imply that there is interplay between inflammation, immune dysregulation and defective development of the lungs in BPD, outlining potential molecular pathways for future targeted therapies.

STRING analysis of the prioritized genes was then performed to identify gene hubs potentially involved in BPD progression. Analysis of the top 10 gene hubs (Figure 3b) identified 9606.ENSP00000265171 to be the top gene based on connectivity. This Ensembl protein corresponded to Epidermal Growth Factor Receptor (EGFR). Further analysis using the STRING network demonstrated a cluster of proteins that interacted with EGFR, including ERBB2, ERBB3, IGF1R and GRB2, which are all involved in growth factor signaling pathways such as the ERBB signaling pathway and PI3K-AKT signaling pathway. These pathways are involved in lung development through the regulation of cell proliferation, survival and differentiation. EGFR signalling pathway disruption has been implicated in defective alveolar and vascular development, which are both core to the development of BPD. As EGFR has high connectivity and plays a central role in growth factor networks, the gene may represent a critical regulatory point in the disrupted signaling observed in BPD. These findings suggest that further investigation of EGFR and its interacting genes and pathways could be the source of potential therapeutic targets for reducing injury and allowing for proper lung development in neonates at risk for BPD.



### Rodent - broad - systematic review info
<!-- Summary of rodent results -->
22 murine BPD studies yielded 33 gene lists for analysis using MAIC (23 ranked and 10 unranked). Of the 22 studies, 14 used mice models and 8 used rat models. The majority (19/22 86%) of these studies modelled BPD by exposing murine models to hyperoxic environments. Other methods included lipopolysaccharide (LPS) treatment and induced low birth weight. 

### Rodent - specific - MAIC analysis
<!-- Specific results worth highlighting -->
GO biological processes (FDR 0.01). Top 50 enriched terms in bubble plot (figure)

Vasculature Development (GO:0001944), Angiogenesis (GO:0001568), Blood Vessel Morphogenesis (GO:0048514), and Blood Vessel Development (GO:0001525) were all among the top 50 significantly enriched terms. 

Programmed Cell Death, Apoptotic Process, Cell Death

Defense Response, Response to Cytokine, Response to stress

### Overlap
<!-- Summary of overlap -->

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
