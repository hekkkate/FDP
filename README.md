# Insights of the Genomic Landscape of Holocentric Chromosomes in the Spider _Dysdera catalonica_


## Final Degree Project
- **Title:** Insights of the Genomic Landscape of Holocentric Chromosomes in the Spider _Dysdera catalonica_
- **Author:** Hekate Ribera
- **Degree:** Bachelor`s Degree in Bioinformatics (BDBI)
- **Institution:** ESCI-UPF
- **Course:** 2023-2024
- **Date:** 18/06/2023

## Description

This repository contains data and Python code from the research conducted on the genomic landscape of holocentric chromosomes in the spider _Dysdera catalonica_. The project involves analyzing genomic data to understand the structure and function of these chromosomes.


## Repository Structure

**Data**

Contains datasets used in the analysis:

- **_D. catalonica_:** Data related to _Dysdera catalonica_.
  - **TADS:** Files with TAD (Topologically Associating Domains) blocks at different resolutions.
  - **tad_centro.bed:** Centromere data for TADs.
- **CENH3:** Data on CENH3 peaks.
  - **CENH3_peaks_sorted.50kb.merged.bed:** Sorted and merged CENH3 peak data.
- **Parameters:** Various parameter files for quartet analysis.
  - **merged.quartet.*.centromeres:** Files with centromere data at different resolutions.
- **_R. pubera_:** Data related to Rhynchospora pubera.
    - **R_pubera_ref_2n10_v2_Tyba.bed:** Reference data for R. pubera.
    - **Rhynchospora_info.txt:** Information on Rhynchospora.
    - **Cross_RpubCentromeres_with_QuartetCandidates:** Cross-analysis data between R. pubera centromeres and quartet candidates.
      - **2_BedtoolsCluster:** Clustered data using Bedtools.

**quarTeT**

Contains scripts and results for the quartet analysis:

- **quartet_centrominer.py:** Script for centromere mining.
- **quartet.py:** Main script for quartet analysis.
- **quartet_util.py:** Utility functions for quartet analysis.
- **Candidates:** Output files with candidate centromeres and clustered results.
  - **clustered_output.bed:** Clustered output file.
  - **quartet.centromeres.bed:** Identified centromeres.
