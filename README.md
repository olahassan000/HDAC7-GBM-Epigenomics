# Epigenomic-anayalis-Glioblastoma-stem-cells-using-H3K9me3-CHIP-Seq-on-HDAC7-knockdown-vs-CTRL-using-R.
H3K9me3 ChIP-seq analysis of HDAC7-siRNA knocked down patient-derived glioblastoma stem cells to investigate HDAC7-dependent chromatin remodeling and heterochromatin regulation.

# Methods:
- R ( markdown)
- ChIPseeker
- ClusterProfiler
- Gene mapping (CompGO)


# Project Overview :
Glioblastoma (GBM) is characterized by extensive epigenetic plasticity that contributes to tumor-cell state and therapeutic resistance. My doctoral research identified HDAC7 as an epigenetic regulator in GBM and investigated how HDAC7 inhibition affects both transcriptional programs and chromatin organization in patient-derived glioblastoma stem cells (GSCs).

This project focuses on H3K9me3 ChIP-seq analysis following HDAC7 knockdown. H3K9me3 is a repressive histone modification associated with heterochromatin, making it possible to investigate whether HDAC7 depletion alters the distribution and enrichment of repressive chromatin across the genome.

H3K9me3 CHIPseq analysis forms part of a broader multi-omics investigation integrating epigenomic, transcriptomic, and functional approaches to characterize the molecular consequences of HDAC7 inhibition in GBM.

# Research Question

Does HDAC7 inhibition remodel the H3K9me3 landscape in patient-derived GSCs, and what does this reveal about HDAC7-mediated regulation of heterochromatin and cancer-associated transcriptional states?

# Hypothesis

HDAC7 depletion promotes enrichment of the repressive histone modification H3K9me3, contributing to chromatin-state changes associated with transcriptional reprogramming in GSCs.

# Experimental Design :

H3K9me3 CHIPseq was performed on patient-derived GSCs following HDAC7 siRNA knockdown 

- Biological system: Patient-derived GSCs
- Perturbation: HDAC7 knockdown using siRNA
- Comparison: siHDAC7 vs. sicontrol
- Epigebetic mark: H3K9me3
- Assay: Bulk RNA-seq
- Objective: Characterize HDAC7-dependent changes in repressive chromatin
- Approach: Peak calling using SICER 1.1 for mapping enrichment H3K9me3 regions relative to input and CTRL 

