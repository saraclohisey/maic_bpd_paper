Systems-Level Insights into Bronchopulmonary Dysplasia from Meta-Analysis of Genome-Scale Studies

Chris Happs1,2*, Prerna Khanna1,2*, Charlotte Scoynes2, Nelly Muriungi1, Akira Alexander1, Josh Rogers1, Elizabeth Lake1,2, Maximilian Pickup1,2, Nicholas Parkinson1, Jonathan Millar2, Kenneth Baillie1,2, Sara Clohisey Hendry1,2


Running title: MAIC analysis of Bronchopulmonary Dysplasia
 
ABSTRACT

Background
Despite marked improvements in survival following preterm birth, the incidence of bronchopulmonary dysplasia (BPD) continues to rise. BPD remains the most prevalent complication of prematurity and carries the risk of long-term morbidity. Characterising the cellular and molecular mechanisms driving disease progression is critical for informing clinical management and improving outcomes. To this end, we conducted a meta-analysis of genome-scale studies to identify molecular pathways implicated in BPD progression in both human cohorts and animal models.

Methods
Gene lists associated with bronchopulmonary dysplasia in human and rodent models were obtained from systematically identified genome-scale studies. These lists were then analysed using the meta-analysis by information content (MAIC) algorithm, which integrates multiple datasets to produce a single aggregated, ranked gene list based on the cumulative strength of evidence for each gene.

Results


Conclusions

Key words: Bronchopulmonary Dysplasia; adaptive immunity, T cells, 
 
Background

Bronchopulmonary dysplasia (BPD), a chronic lung disease, is one of the most common complications of preterm birth, affecting up to 30% of preterm infants born before 32 weeks post-menstrual age (PMA)1,2,3. Antenatal and postnatal factors disrupt the developing lung leading to decreased alveolarisation, larger alveoli, irregular pulmonary vessels, and fibrotic tissue4,5. The effects of BPD can be life-long; individuals with BPD are more likely to require rehospitalisation during their childhood and to have limited lung function compared to those born preterm without BPD6–9.

Understanding the molecular mechanisms that contribute to BPD could aid in risk prediction, targeted therapies, and understanding disease mechanisms. The heterogeneity of the disease has hampered efforts to identify reliable, consistent biomarkers and causative genes associated with disease progression. Alongside evidence from twin studies pointing to a possible heritable component in BPD 10,11 some putative genetic candidates have been identified (e.g. SPOCK2, CRP)12,13. though no gene has been significantly associated with the development of BPD by genome-scale studies such as Genome Wide Association Studies (GWAS) or exome sequencing 12–16. Recently, transcriptomic data has been used to identify four endotypes of BPD, distinguished by T helper cell and T cell signalling17.

Comparative analyses across species can provide valuable insights into common mechanisms while also highlighting potential species-specific responses across models. Rodent models have been widely employed to study the pathophysiology of BPD. The rodent model has concentrated primarily on hyperoxia-induced lung injury, mimicking the impaired alveolar development and inflammation observed in preterm infants 18. Anatomical and physiological differences have prevented in-depth research of ventilator induced lung injury in this model.

By integrating heterogeneous data sources, we can gain new perspectives. This study incorporates genome-scale insights to complement the field’s longstanding clinical focus.  We conducted two concurrent systematic reviews of the BPD literature, focusing on genome-scale studies in humans and animal models. Results were extracted from identified studies, where possible, and analysed using the Meta Analysis by Information Content (MAIC) algorithm. This is a previously described algorithm that uses data-driven gene list weightings to produce a comprehensive ranked list of genes associated with the trait of interest 19–22.

Our findings show that genes associated with development and maintenance of adaptive immune cells feature prominently, suggesting that adaptive-lineage cells may play a larger role in BPD pathogenesis, and potentially a wider role in ventilator associated lung injury, than previously appreciated.

Results

Systematic review 
We first conducted a systematic review of studies that reported associations between genes, transcripts, or proteins, and the development of BPD in humans or the study of BPD in non-human mammalian models (Supplementary Methods). We did not restrict the search terms to a specific definition of BPD; however, the timeline of genome-scale studies results in an indirect emphasis on more recent BPD definitions. Our search yielded 4450 unique citations that were evaluated for inclusion (Supplementary Figures 1 and 2). For full text evaluation we retrieved 76 articles for human studies and 118 for mammalian studies, without overlap. Although large, non-human mammalian models are used to explore BPD,23,24 we did not identify any that met our inclusion criteria (Supplementary Tables 1 and 2) and further analysis therefore focused on rodent models, such as mice and rats.

Meta-Analysis by Information Content of human genome-scale Bronchopulmonary Dysplasia studies
From 76 human studies, 21 met our eligibility criteria (Supplementary Figure 1, Table 1), yielding 31 gene lists (23 ranked and 8 unranked) employing 5 experimental techniques (Supplementary Table 3). The included studies represented 4358 infants (cases = 2247, controls = 2111).  While the definition of BPD varied between studies, over two-thirds of studies, (71.4%, 15/21), used receipt of respiratory support at 36 weeks PMA 3 (Table 1). All but a single study used primary tissue or blood 25. MAIC collated and ranked 8017 unique genes across the datasets (Supplementary Table 4), and the top 25 are shown here (Figure1A; Top 100 in Supplementary Figure 3A). A single gene was supported by evidence from 4 experimental techniques (RASGRP3, rank = 1). Few genes (n = 53 genes, 0.6%) were supported by >=3 methods while 745 genes (9.74%) were supported by more than 1 method. In the top 10 ranked genes we observe immune regulation (RASGRP3, CD2, GPA33, IL1R2, CD177) and extracellular structure (CHIT1, RCAN3, LRRN3, FBN1). Additionally, a subunit of foetal haemoglobin, HGB1, features. Although the top hit (RASGRP3) is supported by data from GWAS experiments, these contributed very little information content to the top ranked genes overall (Supplementary Figure 3B). Cell type–specific enrichment analysis indicates that the gene rankings are most strongly driven by cells of the lymphoid lineage 26 (Supplementary Figure 4).

Enrichment analyses of Human BPD MAIC gene set
Multiple aspects of T cell activation were highlighted by gene set enrichment analysis (GSEA) of the gene set using the Reactome database (Figure 1B). These were seen alongside signals from various aspects of immunity and supported by searches of other databases (See Supplementary materials). The signal was primarily driven by a core set of 23 genes (Supplementary Figure 3C), which the Markov Cluster Algorithm (MCL) partitioned into two distinct modules (Figure 1C): one linked to carbohydrate digestion and absorption and a second associated with CD3 and TCR zeta-chain phosphorylation. The latter constituted the substantially larger module, encompassing multiple T cell receptor components as well as several elements of the HLA complex.

We prioritised 945 genes for further investigation (Supplementary Figure 3D), as previously described 22 and of these 310 (38%) were identified as druggable (Supplementary Materials), according to The Druggable Genome27. We performed Over Representation Analysis (ORA), on the prioritised gene set. The Reactome database replicated much of the signal observed in the GSEA (Supplementary Materials). We grouped ORA results from the Gene Ontology database (encompassing all ontologies) first based on semantic similarity, and then based on function (Figure 1C)28. Our analysis reveals an over-representation of immune system processes associated with lymphoid-mediated immunity, particularly regulation of T cell activation. 

Protein-protein Interaction network of Human BPD MAIC gene set
We created a protein-protein interaction (PPI) network using the prioritised gene set. Clustering of this network using the Markov Cluster Algorithm (MCL) identified 25 clusters with >=5 members. The 7 largest clusters contained >=10 members (Supplementary Figures 5 A-E show the top 5 clusters). Using previously reported methods (Millar et al., 2024), we identified 32 hub proteins likely to play central roles in the broader PPI network (Supplementary Figure 5 F). MCL clustering of this hub revealed three major clusters related to lymphocyte function, corresponding to activation (red, blue), receptor regulation (blue), and immunoglobulins (green) (Figure 1E). Overall, our analysis identified a robust lymphoid cell signature across a diverse range of genome-scale studies of BPD.

Comparative analysis with ARDS MAIC gene set
Acute lung injury caused or worsened by mechanical ventilation during treatment is a feature of BPD in neonates and Acute Respiratory Distress Syndrome (ARDS) in adults (paediatric ARDS in children). We wished to characterise, firstly, the shared of effects mechanical ventilation may have on the developed and the developing lung, and to understand distinct factors that may underlie each syndrome. We evaluated the human BPD MAIC dataset against our previously generated ARDS MAIC analysis 22.

Focusing on the prioritised genes from both datasets, ORA highlighted shared pathology relating to regulation of T cell activation alongside leukocyte cell activation (Figure 2A). There were 112 genes that overlapped in the prioritised gene set lists, (Figure 2B) and this overlap was found to be significant (p<0.005) and the overlap occurred primarily toward the top of the ranked lists (Supplementary Figure 6A). Over representation analysis further highlighted leukocyte-mediated immunity, lymphocyte-mediated immunity, and positive regulation of both T cells and type II interferon in the overlapping genes (Figure 2C). A PPI network focused on the overlap between datasets identifies 6 clusters of >=3 genes (Figure 2D), the largest of which (red) reflects the lymphocyte signal seen elsewhere.

Meta-Analysis by Information Content of genome-scale rodent Bronchopulmonary Dysplasia studies
Rodent systems are widely used to model BPD. From 20 eligible rodent BPD studies (Supplementary Figure 2, Table 2) we extracted and analysed 35 gene lists (28 ranked and 7 unranked), employing 5 experimental techniques (Supplementary Table 3). Of these studies, 13 used mice models and 7 used rat models. To enable cross-species comparisons, we mapped the genes from both species to their human ortholog symbols as part of the MAIC workflow. The majority (17/20; 85%) of studies modelled BPD by exposing neonatal pups to a hyperoxic environment, though the approaches differed. For example, there was variation in the timeframe of hyperoxia (from 3 days to 14 days), recovery in room air (0 days to 57 days), continuous versus intermittent hyperoxia, and the percentage oxygen (70 – 100%) used across the studies. Other methods to model BPD in rodent models included lipopolysaccharide (LPS) treatment (1 study) and induced IUGR through maternal diet (1 study). MAIC collated 7637 genes across all datasets (Figure 3A; Supplementary Table 5; Top 100 in Supplementary Figure 7A) and the top 3 genes were supported by evidence from >=4 experimental techniques (RAC2, CXCR2, IL1R2).  One in five genes were supported by more than 1 method (n = 1597, 20.91%), with 141 genes (1.85%) supported by >=3 methods.  Immune processes are broadly highlighted within the top ten genes (RAC2, CXCR2, IL1R2, CCDC3, PTGS2). Notably, IL1R2 appears among the top 10 results in both human (rank = 3) and rodent (rank = 3) BPD MAIC analyses. Gene rankings are strongly driven by fibroblast cells, with far less emphasis on the lymphoid cells seen in the human dataset, according to cell type–specific enrichment analysis (Supplementary Figure 8).

Enrichment analyses of Rodent BPD MAIC gene set
Gene set enrichment analysis of the rodent MAIC gene set, using the Reactome database, indicates strong signals for mRNA and translation associated pathways (Figure 3B). Analysis of the ranked genes contributing to this signal (Supplementary Figure 7C), shows a cluster of lower ranked genes (r >2500) that drive these signals. To fully exploit the power of MAIC, we prioritised the top 1783 genes from the rodent BPD gene set for further investigation (Supplementary Figure 7D). Gene ontology ORA revealed a significant overrepresentation of pathways related to leukocyte cells migration and activation, and extracellular matrix organisation (Figure 3C). An MCL clustered PPI network identified 55 clusters with >=5 members (Supplementary Figure 9). The 21 largest clusters contained >=10 members. Among these, we found programs associated with the adaptive immune response and mitosis. Using the PPI network we identified 13 hub genes, including FC gamma receptors (FCGR1A, FCGR2A, FCGR2B) and lymphocyte markers (CD3E, CD2), suggested as being central to the wider network in rodent models of BPD (Figure 3D).

Comparative analysis of Human and Rodent BPD MAIC gene sets
Ontology ORA showed that while the lymphoid signal observed in humans above was seen in the rodent gene set, we also saw the role of the extracellular matrix and wound healing highlighted (Figure 4A). The gross overlap between the two parallel MAIC analyses carried out in this study was not shown to be significant by hypergeometric test (p>0.5) (Supplementary Table 6). However, focusing on the prioritised genes from both gene sets indicated the overlap of 163 genes (Figure 4B) was significant (Supplementary Table 6). The similarity occurred predominantly toward the top of the prioritised lists (Figure 6B).

An MCL-clustered PPI network of the overlapping genes between the prioritised sets revealed five distinct clusters (Figure 4D). These clusters prominently featured T cell receptor–associated genes, including those linked to primary immunodeficiency and ZAP-70 translocation, as well as genes involved in mitosis. Notably, the overlap also highlighted B-cell receptor signalling pathways which was absent from either dataset when analysed independently, alongside IL-1 signalling, which was shared across both datasets.

 
Discussion
The clinical and biological heterogeneity of BPD presents challenges for identifying the molecular processes that drive progression of the disease. To address this, we applied a validated in silico approach to systematically integrate and prioritise existing genome-scale BPD datasets from both human and rodent studies.  Further to this, we compared our human BPD MAIC results to our previously generated ARDS MAIC dataset. 

Our findings heavily prioritise elements of the adaptive immune response, in particular development and activation of T cells. This signal was seen across all three gene sets examined (Human, Rodent, ARDS). And for BPD is not without foundation within the literature.  A recent study of potential transcriptomic endotypes in BPD focused on the Pietrzyk dataset included in our analysis17,29. and identified 4 potential endotypes underlying BPD progression. T helper 17 (Th17) differentiation emerged as the most significant pathway distinguishing the BPD endotypes.  CD4+ T cells were shown to be reduced in infants who develop BPD.30  While, a lower CD4/CD8 ratio has been observed in adults with a history of BPD31. These taken together with our results, suggest a central role for T cells in the progression and of BPD.

Only 12% of the prioritised BPD gene set overlapped with the ARDS gene set. This was surprising given the shared aetiologies and similarity in sample type between both studies but may reflect the ages of the populations studied and divergence in underlying causes.
Despite the limited overlap, comparison of the ARDS and BPD gene sets further highlighted the role of lymphoid cells in ventilator associated injury. Emphasis is placed on the activation of leukocytes, their role in antigen presentation and innate/adaptive crosstalk. Lymphocyte differentiation is notably absent in ARDS.

The primary goal of carrying out parallel MAIC analyses between human and animal model BPD studies was to differentiate species-specific responses to injury, from core conserved disease mechanisms. The rodent analysis showed a more pronounced focus on pathways associated with extracellular matrix (ECM) remodelling, and wound healing (Figure 4A). The cause of this divergence is multifactorial but may be driven partly by the sample source bias inherent in the existing literature. Over half of the human studies used circulating blood samples (52.4%), which is ideal for capturing systemic immune and biomarker signals. Conversely, most of the rodent studies (19/20) used whole lung tissue, directly capturing the local pathology and the extensive tissue remodelling inherent to the structural component of BPD. Only 2 of our included human studies use lung tissue as their sample source, limiting our ability to explore this further using our methodology.

Despite the difference in their systemic and local pathologies, the significant overlap between the prioritised human and rodent lists (163 genes) points towards a conserved set of critical mechanisms. This convergence is most clearly demonstrated by the shared presence of Interleukin-1 Receptor Type 2 (IL1R2) in the top ranked genes of the human (rank = 3) and rodent (rank = 3) datasets. This finding anchors the disease in the context of the perinatal hypoxic-inflammatory environment. IL1R2 is upregulated in acute hypoxia,32  and functions as a decoy receptor, acting as a crucial endogenous brake on the potent pro-inflammatory signalling cascade initiated by Interleukin-1 (IL-1) 33. The preterm lung is uniquely vulnerable to hypoxia, which can trigger a dangerous, self-amplifying cycle of injury and inflammation34. IL-1 antagonism has been shown to confer protection in rodent models of BPD,35,36 suggesting that IL1R2 may exert a protective role as an anti-inflammatory ‘brake’ protein in this context. 

Throughout, the differential immune signal (leukocyte-cell-related immunity versus lymphoid-cell-related immunity) may represent a genuine biological difference occurring over the disease time course. While the leukocyte signal may represent the acute, innate driven injury phase, as BPD continues a prolonged course it involves a broader and more protracted inflammatory process where the cells of the lymphoid lineage play a more influential, and potentially damaging role.

This study is based on the published literature and is intended to capture the current state of genome-wide BPD research. It is subject to several limitations. Firstly, blood is among the least invasive and most practical biological samples to collect in the NICU setting. As detailed above, this difference in sample source for human and rodent data represents a primary limitation on direct comparability and interpretation of tissue-specific pathology. Secondly, due to experimental methodologies, the rodent models of BPD included in this analysis may not accurately reflect the human disease but summarise the effects of hyperoxia induced during disease. Thirdly, due to key developmental differences - such as timing of alveolarisation and immune system maturation – the results may not be directly comparable between species. It is difficult to determine if some uncommon, enriched pathways reflect rodent-specific responses to experimental injury rather than universally conserved disease mechanisms. Finally, MAIC does not account for direction of effect, thus we are limited on how much we can infer about specific mechanisms.

In summary, MAIC offers a validated, integrative strategy capable of navigating the substantial clinical and molecular heterogeneity that characterises BPD. Through this framework, we identified a set of consensus genes across diverse genome-scale datasets. Notably, the aggregated signal is concentrated within lymphoid lineage signatures and underscores key processes involved in T cell activation and development.

 
Methods

Systematic review
The systematic review and meta-analysis protocol was registered with the International Prospective Register of Systematic Reviews (PROSPERO; CRD42022306270, CRD42024550229). The review is reported in compliance with the Preferred Reporting Items for Systematic Reviews and Meta-Analyses (PRISMA) guidelines.37

Search strategy and selection criteria
A detailed description of our search strategy and eligibility criteria is provided in the Supplementary Methods. Briefly, we searched MEDLINE, Embase without language restrictions on 24/05/2024. We included human genome-wide studies reporting associations between genes, transcripts, or proteins. For human studies we accepted any contemporaneous BPD definition. For rodent studies, definitions of BPD study groups were accepted as hyperoxic exposure and induced low birth weight. We excluded candidate in vivo or in vitro studies (< 50 genes/proteins), candidate gene associations, and studies with <5 patients per arm. Following deduplication, titles were initially screened using Screenatron.38 

Abstracts were then screened against eligibility criteria, this included organising the studies into separate collections of human and animal studies, with an independent author resolving inconsistencies. Full texts were retrieved and analysed for inclusion before extraction of gene lists for inclusion in MAIC. Input lists were processed as previously described.20,22,39 Briefly, lists were considered ranked if metrics of statistical significance (p-value) and/or fold change (FC) were reported. These lists were ordered by p-value/false discovery rate (low to high) then, where applicable, by absolute fold change or effect size (high to low). Gene names were converted to HGNC gene symbols (or Ensembl/Refseq symbols if no HGNC symbol). Rodent data was mapped to human ortholog symbols using custom scripts to allow for comparison with the human MAIC results.

MAIC
The MAIC algorithm has previously been described in detail.19–22,39 A full description and the source code is available at https://baillielab.net/maic. We implemented pymaic v0.2 in Python v3.9 and used Technique to categorise input lists. MAIC combines both ranked and unranked lists, of unknown quality, to build a comprehensive ranked list of entities according to 4 basic assumptions.1. There is a set of true positives (genes implicated in BPD), 2.  A gene is more likely to be a true positive if it appears in datasets from more than one source, 3. A gene is more likely to be a true positive if it appears in datasets with a higher proportion of replicated genes. 4. A gene is more likely to be a true positive if it appears in datasets from multiple methods or modalities. 

Functional analyses and tissue expression
All enrichment and over representation analyses were implemented using clusterProfiler (v4.0)28 in R (v4.5.1) and visualised using functions in that package. Code is available at All code is available at https://github.com/baillielab/bpd_maic. Redundancy of enriched GO terms was removed using the simplify function. Hypergeometric tests were implemented with the 1-phyper function in R. Gene overlaps were visualised using ggvenn. We conducted cell-type specific enrichment analysis using WebCSEA26 and extracted the top 20 general cell types for each query. The Drug Gene Interaction Database (DGIdb)  was queried for each ranked gene 27.

Protein-protein Interaction Network
Prioritised genes were analysed using the online tool STRING (https:// string-db.org) to determine potential protein-protein interactions (PPI). For humans 919 genes were mapped, for rodents 1726.  A PPI network was constructed using the MCL (Markov Clustering) algorithm, with an inflation parameter of 3 and focused on high confidence (interaction score of >= 0.7) interactions. While network graphs represent evidence from all active interaction sources, only coexpression interactions are displayed.  The network was exported and hub genes subsequently identified using CytoHubba 0.1 implemented in CytoScape 3.10.3. The overlap of the top 100 ranked genes, ranked using 5 common algorithms (MCC, MNC, Degree, EPC and DMNC), was used to evaluate hub genes. 

Overlap Analysis of Ranked Gene Lists
To assess the degree of similarity between ranked lists, we computed the percent overlap at incremental list lengths. Beginning with the top-ranked gene from each list, we iteratively increased the comparison window by one gene until reaching a maximum of n genes. At each step, the proportion of overlapping genes was calculated as the number of shared genes divided by the number of genes included at that step, expressed as a percentage.

 
References
1.	Neonatal Data Analysis Unit (NDAU). Neonatal Health Intelligence Tool. 2021. Available: https://www.imperial.ac.uk/neonatal-data-analysis-unit/neonatal-data-analysis-unit/neonatal-data-visualisations/.
2.	Isayama, T. et al. Revisiting the Definition of Bronchopulmonary Dysplasia: Effect of Changing Panoply of Respiratory Support for Preterm Neonates. JAMA Pediatr. 171, 271 (2017).
3.	Jensen, E. A. et al. The Diagnosis of Bronchopulmonary Dysplasia in Very Preterm Infants. An Evidence-based Approach. Am. J. Respir. Crit. Care Med. 200, 751–759 (2019).
4.	Gilfillan, M., Bhandari, A. & Bhandari, V. Diagnosis and management of bronchopulmonary dysplasia. BMJ n1974 (2021) doi:10.1136/bmj.n1974.
5.	Thébaud, B. et al. Bronchopulmonary dysplasia. Nat. Rev. Dis. Primer 5, 78 (2019).
6.	Greenough, A. Measuring respiratory outcome. Semin. Neonatol. 5, 119–126 (2000).
7.	Greenough, A. Bronchopulmonary dysplasia – Long term follow up. Paediatr. Respir. Rev. 7, S189–S191 (2006).
8.	Dassios, T. & Greenough, A. Long-term sequelae of bronchopulmonary dysplasia. in Respiratory Diseases of the Newborn Infant (eds Sinha, I. P., Bhatt, J. M., Cleator, A. & Wallace, H.) 68–78 (European Respiratory Society, Sheffield, United Kingdom, 2021). doi:10.1183/2312508X.10013720.
9.	Sun, T., Yu, H.-Y., Yang, M., Song, Y.-F. & Fu, J.-H. Risk of asthma in preterm infants with bronchopulmonary dysplasia: a systematic review and meta-analysis. World J. Pediatr. 19, 549–556 (2023).
10.	Lavoie, P. M., Pham, C. & Jang, K. L. Heritability of Bronchopulmonary Dysplasia, Defined According to the Consensus Statement of the National Institutes of Health. Pediatrics 122, 479–485 (2008).
11.	Bhandari, V. et al. Familial and Genetic Susceptibility to Major Neonatal Morbidities in Preterm Twins. Pediatrics 117, 1901–1906 (2006).
12.	Hadchouel, A. et al. Identification of SPOCK2 As a Susceptibility Gene for Bronchopulmonary Dysplasia. Am. J. Respir. Crit. Care Med. 184, 1164–1170 (2011).
13.	Mahlman, M. et al. Genome-wide association study of bronchopulmonary dysplasia: a potential role for variants near the CRP gene. Sci. Rep. 7, 9271 (2017).
14.	Wang, H. et al. A Genome-Wide Association Study (GWAS) for Bronchopulmonary Dysplasia. Pediatrics 132, 290–297 (2013).
15.	Ambalavanan, N. et al. Integrated Genomic Analyses in Bronchopulmonary Dysplasia. J. Pediatr. 166, 531-537.e13 (2015).
16.	Torgerson, D. G. et al. Ancestry and genetic associations with bronchopulmonary dysplasia in preterm infants. Am. J. Physiol.-Lung Cell. Mol. Physiol. 315, L858–L869 (2018).
17.	Moreira, A. G. et al. Leveraging transcriptomics to develop bronchopulmonary dysplasia endotypes: a concept paper. Respir. Res. 24, (2023).
18.	Hurskainen, M. et al. Single cell transcriptomic analysis of murine lung development on hyperoxia-induced damage. Nat. Commun. 12, (2021).
19.	The GenOMICC Investigators et al. Genetic mechanisms of critical illness in COVID-19. Nature 591, 92–98 (2021).
20.	Parkinson, N. et al. Dynamic data-driven meta-analysis for prioritisation of host genes implicated in COVID-19. Sci. Rep. 10, 22303 (2020).
21.	Wang, B. et al. Systematic comparison of ranking aggregation methods for gene lists in experimental results. Bioinformatics 38, 4927–4933 (2022).
22.	Millar, J. E. et al. The genomic landscape of Acute Respiratory Distress Syndrome: a meta-analysis by information content of genome-wide studies of the host response. Preprint at https://doi.org/10.1101/2024.02.13.24301089 (2024).
23.	Eiby, Y. A. et al. A Pig Model of the Preterm Neonate: Anthropometric and Physiological Characteristics. PLoS ONE 8, e68763 (2013).
24.	Rozance, P. J. et al. Intrauterine growth restriction decreases pulmonary alveolar and vessel growth and causes pulmonary artery endothelial cell dysfunction in vitro in fetal sheep. Am. J. Physiol.-Lung Cell. Mol. Physiol. 301, L860–L871 (2011).
25.	Tsotakos, N. et al. All trans-retinoic acid modulates hyperoxia-induced suppression of NF-kB-dependent Wnt signaling in alveolar A549 epithelial cells. PloS One 17, (2022).
26.	Dai, Y. et al. WebCSEA: web-based cell-type-specific enrichment analysis of genes. Nucleic Acids Res. 50, W782–W790 (2022).
27.	Freshour, S. L. et al. Integration of the Drug–Gene Interaction Database (DGIdb 4.0) with open crowdsource efforts. Nucleic Acids Res. 49, D1144–D1151 (2021).
28.	Wu, T. et al. clusterProfiler 4.0: A universal enrichment tool for interpreting omics data. The Innovation 2, 100141 (2021).
29.	Pietrzyk, J. J. et al. Gene expression profiling in preterm infants: new aspects of bronchopulmonary dysplasia development. PloS One 8, (2013).
30.	Lymphocyte Subpopulations in Bronchopulmonary Dysplasia. Am. J. Perinatol. 20, 465–476 (2003).
31.	Um-Bergström, P. et al. Increased cytotoxic T-cells in the airways of adults with former bronchopulmonary dysplasia. Eur. Respir. J. 60, 2102531 (2022).
32.	Johnson, D. R., O’Connor, J. C., Hartman, M. E., Tapping, R. I. & Freund, G. G. Acute hypoxia activates the neuroimmune system, which diabetes exacerbates. J. Neurosci. Off. J. Soc. Neurosci. 27, 1161–1166 (2007).
33.	Peters, V. A., Joesting, J. J. & Freund, G. G. IL-1 receptor 2 (IL-1R2) and its role in immune regulation. Brain. Behav. Immun. 32, 1–8 (2013).
34.	Eltzschig, H. K. & Carmeliet, P. Hypoxia and inflammation. N. Engl. J. Med. 364, 656–665 (2011).
35.	Nold, M. F. et al. Interleukin-1 receptor antagonist prevents murine bronchopulmonary dysplasia induced by perinatal inflammation and hyperoxia. Proc. Natl. Acad. Sci. 110, 14384–14389 (2013).
36.	Bui, C. B. et al. Interleukin-1 Receptor Antagonist Protects Newborn Mice Against Pulmonary Hypertension. Front. Immunol. 10, 1480 (2019).
37.	Page, M. J. et al. The PRISMA 2020 statement: an updated guideline for reporting systematic reviews. BMJ n71 (2021) doi:10.1136/bmj.n71.
38.	Clark, J. et al. A full systematic review was completed in 2 weeks using automation tools: a case study. J. Clin. Epidemiol. 121, 81–90 (2020).
39.	Li, B. et al. Genome-wide CRISPR screen identifies host dependency factors for influenza A virus infection. Nat. Commun. 11, 164 (2020).
40.	Ahmed, S. et al. Proteomics-Based Mapping of Bronchopulmonary Dysplasia-Associated Changes in Noninvasively Accessible Oral Secretions. J. Pediatr. 270, (2023).
41.	Bhattacharya, S. et al. Genome-wide transcriptional profiling reveals connective tissue mast cell accumulation in bronchopulmonary dysplasia. Am. J. Respir. Crit. Care Med. 186, (2012).
42.	Bhattacharya, S. et al. Lymphocyte-Specific Biomarkers Associated With Preterm Birth and Bronchopulmonary Dysplasia. Front. Immunol. 11, (2020).
43.	De Paepe, M. E., Greco, D. & Mao, Q. Angiogenesis-related gene expression profiling in ventilated preterm human lungs. Exp. Lung Res. 36, (2010).
44.	Dai, D. et al. Bronchopulmonary Dysplasia Predicted by Developing a Machine Learning Model of Genetic and Clinical Information. Front. Genet. 12, (2021).
45.	Fulton, C. T., Cui, T. X., Goldsmith, A. M., Bermick, J. & Popova, A. P. Gene Expression Signatures Point to a Male Sex-Specific Lung Mesenchymal Cell PDGF Receptor Signaling Defect in Infants Developing Bronchopulmonary Dysplasia. Sci. Rep. 8, (2018).
46.	Gong, X., Qiu, J., Qiu, G. & Cai, C. Adrenomedullin regulated by miRNA-574-3p protects premature infants with bronchopulmonary dysplasia. Biosci. Rep. 40, (2020).
47.	Hamvas, A. et al. Exome sequencing identifies gene variants and networks associated with extreme respiratory outcomes following preterm birth. BMC Genet. 19, (2018).
48.	Li A. et al. Investigating the early mechanisms leading from ventilation-induced lung injury to bronchopulmonary dysplasia using in vitro lung cell over-distension. J. Paediatr. Child Health 51, (2015).
49.	Luo, X. et al. Identification of genetic susceptibility in preterm newborns with bronchopulmonary dysplasia by whole-exome sequencing: BIVM gene may play a role. Eur. J. Pediatr. 182, (2023).
50.	Oji-Mmuo, C. N. et al. Tracheal aspirate transcriptomic and miRNA signatures of extreme premature birth with bronchopulmonary dysplasia. J. Perinatol. Off. J. Calif. Perinat. Assoc. 41, (2021).
51.	Siddaiah, R. et al. Multiomics endotyping of preterm infants with bronchopulmonary dysplasia and pulmonary hypertension-A pilot study. Pulm. Circ. 13, (2023).
52.	Windhorst, A. C. et al. Monocyte signature as a predictor of chronic lung disease in the preterm infant. Front. Immunol. 14, (2023).
53.	Zasada, M. et al. Comparative two time-point proteome analysis of the plasma from preterm infants with and without bronchopulmonary dysplasia. Ital. J. Pediatr. 45, (2019).
54.	Al-Mudares, F. et al. Loss of growth differentiation factor 15 exacerbates lung injury in neonatal mice. Am. J. Physiol. Lung Cell. Mol. Physiol. 325, (2023).
55.	Bao, T.-P., Wu, R., Cheng, H.-P., Cui, X.-W. & Tian, Z.-F. Differential expression of long non-coding RNAs in hyperoxia-induced bronchopulmonary dysplasia. Cell Biochem. Funct. 34, (2016).
56.	Bhaskaran, M. et al. Identification of microRNAs changed in the neonatal lungs in response to hyperoxia exposure. Physiol. Genomics 44, (2012).
57.	Chao C.-M. et al. Fgf10 Deficiency Leads to Disturbed Formation of Alveolar Epithelial Cell Type II (AEC II) Which Causes Lethality in a Mouse Model of Bronchopulmonary Dysplasia. vol. 4 http://ovidsp.ovid.com/ovidweb.cgi?T=JS&PAGE=reference&D=emed18&NEWS=N&AN=616934541 (2017).
58.	Chen, K., Jiang, P., Deng, S. & Wang, N. [Expression of thyroid transcription factor-1 and vimentin in neonatal mice with bronchopulmonary dysplasia]. Nan Fang Yi Ke Da Xue Xue Bao 32, (2012).
59.	Cheng, H.-R. et al. Deep Illumina sequencing reveals differential expression of long non-coding RNAs in hyperoxia induced bronchopulmonary dysplasia in a rat model. Am. J. Transl. Res. 9, (2017).
60.	Coarfa, C. et al. Sexual dimorphism of the pulmonary transcriptome in neonatal hyperoxic lung injury: identification of angiogenesis as a key pathway. Am. J. Physiol. Lung Cell. Mol. Physiol. 313, (2017).
61.	Denervaud, V., Gremlich, S., Trummer-Menzi, E., Schittny, J. C. & Roth-Kleiner, M. Gene expression profile in newborn rat lungs after two days of recovery of mechanical ventilation. Pediatr. Res. 78, (2015).
62.	Dong, N. et al. Intratracheal administration of umbilical cord-derived mesenchymal stem cells attenuates hyperoxia-induced multi-organ injury via heme oxygenase-1 and JAK/STAT pathways. World J. Stem Cells 14, (2022).
63.	Dravet-Gounot, P. et al. Lung microRNA deregulation associated with impaired alveolarization in rats after intrauterine growth restriction. PloS One 12, (2017).
64.	El Saie, A. et al. Metabolome and microbiome multi-omics integration from a murine lung inflammation model of bronchopulmonary dysplasia. Pediatr. Res. 92, (2022).
65.	Natarajan, V. et al. Expression Profiling of Genes Regulated by Sphingosine Kinase1 Signaling in a Murine Model of Hyperoxia Induced Neonatal Bronchopulmonary Dysplasia. vol. 18 http://ovidsp.ovid.com/ovidweb.cgi?T=JS&PAGE=reference&D=med14&NEWS=N&AN=28851267 (2017).
66.	Nichols, J. L. et al. Genome-wide association mapping of acute lung injury in neonatal inbred mice. FASEB J. Off. Publ. Fed. Am. Soc. Exp. Biol. 28, (2014).
67.	Nitkin, C. R. et al. FOSL1 is a novel mediator of endotoxin/lipopolysaccharide-induced pulmonary angiogenic signaling. Sci. Rep. 10, (2020).
68.	Rao, S., Liu, M., Iosef, C., Knutsen, C. & Alvira, C. M. Endothelial-specific loss of IKKbeta disrupts pulmonary endothelial angiogenesis and impairs postnatal lung growth. Am. J. Physiol. Lung Cell. Mol. Physiol. 325, (2023).
69.	Revhaug, C. et al. Immune System Regulation Affected by a Murine Experimental Model of Bronchopulmonary Dysplasia: Genomic and Epigenetic Findings. Neonatology 116, (2019).
70.	Scaffa, A. et al. Single-cell transcriptomics reveals lasting changes in the lung cellular landscape into adulthood after neonatal hyperoxic exposure. Redox Biol. 48, (2021).
71.	Shrestha, A. K. et al. Interactive and independent effects of early lipopolysaccharide and hyperoxia exposure on developing murine lungs. Am. J. Physiol. Lung Cell. Mol. Physiol. 319, (2020).

 
CONFLICT OF INTEREST
All authors report no conflicts of interest.

FUNDING
<INSERT>

DATA AVAILABILITY
The MAIC output is included as supplementary material. All code is available at https://github.com/baillielab/bpd_maic.

CONTRIBUTIONS
SCH, JKB and JEM conceived the study. PK, CH, JAR, NM, AA, NP, EL, MP and SCH manually reviewed abstracts for inclusion. PK, CH, SCH, and CS curated the data. PK, CH and SCH did the formal analysis. SCH supervised the study. SCH, PK and CH wrote the original draft of the manuscript. All authors reviewed and edited the manuscript. SCH, PK and CH had access to the raw data. The corresponding author had full access to all the data and final responsibility for the decision to submit for publication.

ACKNOWLEDGEMENTS 
The authors would like to thank Dr. Marie Zechner and Dr. Dominique McCormick for critical reading of the manuscript.



 

Table 1
Study	Technique	Tissue	BPD Definition
Ahmed et al.,40
MassSpec	Oral	Resp. Supp at 36 weeks GA
Ambalavanan et al.,15
GWAS	Blood	Resp. Supp at 36 weeks GA
Bhattacharya et al.,41
Microarray	Lung	Resp. Supp at 36 weeks GA
Bhattacharya et al.,42
RNAseq	Blood	Resp Supp at 3,6,9,12 months 
Da paepe et al.,43
Microarray	Lung	Ventilator dependent for entire lifespan
Dai et al.,44
ExomeSeq	Blood	Rest Supp on 1st day of life, <32 weeks GA
Fulton et al.,45
Microarray	Tracheal aspirates	Resp. Supp at 36 weeks GA
Gong et al.,46
Microarray	Blood	Resp. Supp at 36 weeks GA
Hadchouel et al.,12
GWAS	UCB	Resp. Supp at 36 weeks GA
Hamvas et al.,47
ExomeSeq	Saliva	Resp. Supp at 36 weeks GA
Li et al.,48
ExomeSeq	Blood	Resp. Supp at 36 weeks GA
Luo et al.,49
ExomeSeq	Oral	Resp. Supp at 36 weeks GA 
Oji Mmuo et al.,50
RNAseq	Tracheal aspirates	Resp. Supp at 36 weeks GA
Pietrzyk et al.,29
Microarray	Blood	Resp. Supp and birth <32 weeks GA
Siddaiah et al.,51
RNAseq	Tracheal aspirates	Resp. Supp at 36 weeks GA 
Torgerson et al.,16
GWAS	N/A	Resp. Supp at 36 weeks GA
Tsotakos et al.,25
RNAseq	Cultured cells - A549	NA - cultured cells
Wang et al.,14
GWAS	Blood	Resp. Supp at 36 weeks GA
Windhorst et al.,52
	Microarray	UCB	O2 >21% for 28 days by 36 weeks 
Yuon Chou et al., 	RNAseq	UCB	Resp. Supp at 36 weeks GA
Zasada et al.,53
MassSpec	UCB	Resp. Supp at 36 weeks GA 

Table 1: Characteristics of studies included in Human BPD MAIC analysis. UCB = Umbilical Cord Blood. GA = Gestational age. Resp. Supp = Respiratory support. Oral = Oral mucosa. 


 

Table 2
Study	Technique	Animal	Tissue	Method
Al Mudares et al.,54
RNAseq	Mouse	Whole lung	Hyperoxia
Bao et al.,55
	Microarray	Mouse	Whole lung	Hyperoxia
Bhaskaran et al.,56
Microarray	Rat	Whole lung	Hyperoxia
Bhattacharya et al.,42
RNAseq	Mouse	Whole lung	Hyperoxia
Chao et al.,57
Microarray	Mouse*	Whole lung	Hyperoxia
Chen et al.,58
DNA Methylation	Rat	Whole lung	Hyperoxia
Cheng et al.,59
RNAseq	Rat	Right lung lobe	Hyperoxia
Coarfa et al.,60
RNAseq	Mouse	Whole lung	Hyperoxia
Dénervaud et al.,61
RNA microarray	Rat	Whole lung	Hyperoxia
Na Dong et al.,62
RNAseq	Rat	Whole lung	Hyperoxia
Dravet Gounot et al.,63
RNAseq	Rat	Whole lung	Induced IUGR
El Saie et al.,64
Mass Spec	Mouse	Whole lung	Hyperoxia
Hurskainen et al.,18
scRNAseq	Mouse	Whole lung	Hyperoxia
Natarajan et al.,65
Microarray	Mouse*	Whole lung	Hyperoxia
Nichols et al.,66
QTL analysis	Mouse	Whole lung	NA
Nitkin et al.,67
RNAseq	Mouse	Whole lung	LPS treated
Rao et al.,68
RNAseq	Mouse*	Whole lung	Hyperoxia
Revhaug et al.,69
Microarray	Mouse	Whole lung	Hyperoxia
Scaffa et al.,70
scRNAseq	Mouse	Whole lung	Hyperoxia
Shrestha et al.,71
Microarray	Rat	Whole lung	Hyperoxia

Table 2: Characteristics of studies included in Rodent BPD MAIC analysis. Techniques are outlined in supplementary table X. Mouse* = Mouse line with specific mutation. NA = No treatment. IUGR = Intrauterine growth restriction. LPS = Lipopolysaccharide. 

 

