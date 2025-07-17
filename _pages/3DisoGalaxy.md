---
layout: single
title: "3DisoGalaxy"
permalink: /3DisoGalaxy/
author_profile: true
---

<style>
body {
    font-family: 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue', sans-serif;
    background-color: #000000;
    color: #00FFCC;
    line-height: 1.6;
}

.container {
    max-width: 1000px;
    margin: 0 auto;
    background-color: rgba(10, 10, 10, 0.8);
    padding: 40px;
    border-radius: 8px;
    box-shadow: 0 0 30px rgba(0, 255, 204, 0.2);
}

h1 {
    color: #00FFFF;
    text-align: center;
    font-size: 2.8em;
    margin-bottom: 40px;
    text-shadow: 0 0 15px rgba(0, 255, 255, 0.8);
    letter-spacing: 2px;
    border-bottom: 2px solid #00FFFF;
    padding-bottom: 15px;
}

h2 {
    color: #00BFFF;
    font-size: 2em;
    margin-top: 50px;
    margin-bottom: 20px;
    border-left: 5px solid #00BFFF;
    padding-left: 15px;
    text-shadow: 0 0 10px rgba(0, 191, 255, 0.5);
}

h3 {
    color: #33CCFF;
    font-size: 1.6em;
    margin-top: 30px;
    margin-bottom: 15px;
    border-bottom: 1px dotted #33CCFF;
    padding-bottom: 5px;
}

p, li, table {
    color: #E0E0E0;
    margin-bottom: 10px;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.95em;
    background-color: rgba(30, 30, 30, 0.7);
    border: 1px solid #00BFFF;
}

th, td {
    padding: 12px 15px;
    text-align: left;
    border-bottom: 1px solid rgba(0, 255, 204, 0.3);
}

th {
    background-color: #005555;
    color: #00FFFF;
    font-weight: bold;
    text-transform: uppercase;
}

tr:hover {
    background-color: rgba(0, 255, 204, 0.05);
}

img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 20px auto;
    border: 1px solid #00FFFF;
    box-shadow: 0 0 15px rgba(0, 255, 255, 0.5);
    border-radius: 5px;
}

.prominent-link {
    text-align: center;
    margin: 40px 0;
}

.prominent-link a {
    font-size: 1.8em;
    color: #00FFCC;
    font-weight: bold;
    text-shadow: 0 0 10px rgba(0, 255, 204, 0.5);
    transition: color 0.3s ease;
}

.prominent-link a:hover {
    color: #33CCFF;
}

.code-block {
    background-color: #1a1a1a;
    color: #00FFCC;
    padding: 15px;
    border-radius: 5px;
    overflow-x: auto;
    margin: 20px 0;
}

.project-showcase table {
    background-color: transparent;
    border: none;
    margin: 20px auto;
}

.project-showcase td {
    text-align: center;
    padding: 15px;
    border: none;
    vertical-align: top;
}

.project-showcase img {
    width: 300px;
    height: 180px;
    object-fit: cover;
    border: 1px solid #00FFFF;
    box-shadow: 0 0 15px rgba(0, 255, 255, 0.5);
    border-radius: 5px;
    margin-bottom: 10px;
}

.project-showcase b {
    color: #00FFCC;
    font-size: 1.2em;
    text-shadow: 0 0 10px rgba(0, 255, 204, 0.5);
}
</style>

<div class="container">

# 3DisoGalaxy: A Breast Cancer Protein Isoform Structure Landscape Study

<img src="https://github.com/user-attachments/assets/4a4482e7-d5b8-4507-afca-ff1521371d32" alt="3DisoGalaxy Logo" width="300">

---

## What is 3DisoGalaxy?

**3DisoGalaxy** is a comprehensive bioinformatics resource dedicated to exploring the **protein isoform structural landscape in breast cancer**. This project integrates advanced multi-omics data with artificial intelligence to reveal how alternative splicing events lead to diverse protein isoforms, and how these isoforms influence cancer biology and heterogeneity. Our goal is to provide a platform for identifying novel, subtype-specific therapeutic targets in breast cancer.

This repository provides the complete software and documentation necessary to execute the **Long-Read-Translation-Structomics Workflow** that underpins 3DisoGalaxy.

---

## Background & Rationale: Understanding CLAUDIN18.2 as a Precedent

The success of Claudin18.2 as a targeted therapy in gastric cancer highlights the immense potential of highly specific protein isoforms as therapeutic targets. Understanding the unique expression patterns and structural characteristics of such isoforms is crucial for developing next-generation precision medicines.

For an in-depth understanding of how highly specific targets like Claudin18.2 are identified and validated, please refer to our detailed report:

- [**CLAUDIN18.2 Target: In-Depth Research Report**](/3DisoGalaxy/claudin182/)

This previous work informs our systematic approach in 3DisoGalaxy to uncover similar promising targets in breast cancer.

---

## Explore 3DisoGalaxy Results

Dive into the interactive results of our study, where you can explore the breast cancer protein isoform structure landscape and screen for subtype-specific targets.

<div class="prominent-link">
<a href="http://hkwanglab-compbio.com:3831/">
<img src="https://github.com/user-attachments/assets/d02384b5-b85f-4716-b657-7a122ca92d02" alt="Link to 3DisoGalaxy Web Application">
<br>Access the Interactive 3DisoGalaxy Web Application Here
</a>
</div>

This web application ("3DisoGalaxy") allows you to visualize the intricate network of protein isoform structural similarities and identify potential therapeutic candidates.

---

## Detailed Information on 3DisoGalaxy

### Abstract

When alternative splicing events result in different mature mRNA translated in the cell and diverse protein isoforms produced, they tend to affect disordered protein domains, which are often involved in functionally important protein–protein interactions. Protein isoforms can also have differences in stability, localization, enzymatic activity, and protein–nucleic acid interactions. The extent to which alternative splicing affects protein and/or cell function or, rather, represents a by-product of transcriptome noise is unclear. Breast cancer is one of the most prevalent cancers for women worldwide. Current studies categorize breast cancer into several subtypes according to different receptors and are treated with different clinical methods. The heterogeneity of breast cancer causes this distinct survival outcome difference, and alternative splicing is one of the mechanisms of this heterogeneity. In this study, a comprehensive survey of protein isoform structures in breast cancer tissue was conducted by integrating multiple omics. 90298 ORFs were annotated and filtered by integrating long-read RNA-seq transcriptome analysis and short-read RNA-seq. 79815 ORFs were identified using Ribosome profiling in total. Ultimately, 46202 protein isoforms were kept, and their structures were predicted with AlphaFold2. The "3Diso-TransFold" pipeline constructed the "3DisoGalaxy" protein structural similarity network based on multiple structure alignment scores with evaluated translated ORFs and obtained isoform structures. ORFs from the master transcriptome were retained only if identified by Ribo-seq, supporting their translation. The network reveals breast cancer and TNBC-specific isoforms, enabling subtype-specific therapeutic screening and validation.

<img src="https://github.com/user-attachments/assets/32d0ddfd-540f-49fb-aab3-fd657c5e5d14" alt="Atlas Plan">

### 1. Breast Cancer Alternative Splicing Landscape with Protein Isoform Structure

<img src="https://github.com/user-attachments/assets/4429c7c6-8382-457b-bb00-bbc22bf8b3fe" alt="Breast cancer alternative splicing landscape">

### 2. Screening Subtype-Specific Targets

<img src="https://github.com/user-attachments/assets/b51f9134-de44-4a82-a0ee-d3fe9f88c90f" alt="Screening subtype-specific targets">

### 3. Search Target

<img src="https://github.com/user-attachments/assets/b3d61430-bc01-4d85-b222-c7d47179cb06" alt="Search target">

### 4. About

<img src="https://github.com/user-attachments/assets/25c318a8-cffe-4993-8db8-6af0685e5d1e" alt="About">

### Usage Tutorial

A detailed usage tutorial, including visual guides, is available:

[https://github.com/user-attachments/assets/8dfa4606-e436-4f61-b266-b5d85d438543](https://github.com/user-attachments/assets/8dfa4606-e436-4f61-b266-b5d85d438543)

### Digital Object Identifiers (DOIs) for Datasets

The datasets used in this study, generated through the integration of multi-omics and AI methods to analyze alternative splicing-driven proteoforms, are available on Zenodo (10.5281/zenodo14865747).

| Categories3 Dataset | Project No. | Type | Sample Size | Subtypes | Sequencing Method | Sequencing Platform | Additional Information |
|---------------------|-------------|------|-------------|-----------|-------------------|---------------------|------------------------|
| Assembly | PacBio (in-house) | BC Tissue | 35 | Basal, Her2, LumA, LumB, NAT | PacBio long-read mRNA-seq | PacBio Sequel 2 | Clinical info |
| Discovery set | PRJNA975550 | BC Tissue | 86 | TNBC, Her2, LumA, LumB, NAT | mRNA-seq | Illumina HiSeq 4000 | Clinical info cannot match, no RFS |
| Microbial | PRJNA839244 | BC Tissue | 23 | TNBC, Her2, LumA, LumB, NAT | mRNA-seq | NextSeq 550 | Clinical info, no RFS |
| Validation set | PRJNA486023 | BC Tissue | 90 | TNBC, NAT | mRNA-seq | Illumina HiSeq | Clinical info, RFS |
| Fusion | PRJNA251383 | BC Tissue | 140 | TNBC, ER, NAT | mRNA-seq | Illumina HiSeq 2000 | Clinical information |
| Her2 | PRJNA1018108 | BC Tissue | 156 | Her2, NAT | mRNA-seq | NovaSeq 6000 | - |
| Ribosome profiling | PRJNA898352 | BC Cell line | 24 | - | Ribo-seq & mRNA-seq | Illumina HiSeq 2500 | - |
| Ribosome profiling | PRJNA523167 | BC Cell line | 18 | - | Ribo-seq | Illumina HiSeq 4000 | - |

### 3DisoGalaxy & 3DisoTranFold Pipeline

The pipeline <img src="https://github.com/user-attachments/assets/1eaeaf5c-081d-4d76-b816-bca55d979ad3" alt="3Diso-TransFold Logo" width="100"> [https://github.com/CityUHK-CompBio/3Diso-TransFold](https://github.com/CityUHK-CompBio/3Diso-TransFold), was utilized to evaluate translated ORFs and predict isoform structures from transcriptome-identified transcripts. This process culminated in the construction of **"3DisoGalaxy," a protein structural similarity network** based on multiple structure alignment scores comparing these isoforms. Crucially, ORFs from the master transcriptome were retained only if identified by Ribo-seq analysis, confirming their active participation in the translation process.

We predicted ORF sequences using TransDecoder, combining BLASTP, HMMER, and machine learning methods. After rigorous filtering of low-confidence and short ORFs, the longest ORF sequence for each isoform was selected, and its protein structure was predicted using AlphaFold-2.3. Structural similarity was then quantified using the TMalign method, collecting pairwise isoform similarities to create a comprehensive "protein universe." Furthermore, functional domains and GO term pathway annotations were integrated into the network using UniProtKB databases.

This final network provides a unique view into the landscape of cancer-specific alternative splicing-induced protein isoforms, facilitating the precise screening and validation of subtype-specific isoforms for potential therapeutic applications.

<div class="project-showcase">
<table>
<tr>
<td align="center">
<a href="http://hkwanglab-compbio.com:3831/">
<img src="https://github.com/user-attachments/assets/4a4482e7-d5b8-4507-afca-ff1521371d32" alt="3DisoGalaxy">
<br><b>3DisoGalaxy</b>
</a>
</td>
<td align="center">
<a href="https://github.com/CityUHK-CompBio/3Diso-TransFold">
<img src="https://github.com/user-attachments/assets/c60c5cb0-f865-4689-9130-476feb545052" alt="3DisoTransFold">
<br><b>3DisoTransFold</b>
</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/FeliciaJiangBio/3DisoTarget">
<img src="https://github.com/user-attachments/assets/5d7aab79-7eec-4ae3-9a0a-8a3e8722fb2e" alt="3DisoTarget">
<br><b>3DisoTarget</b>
</a>
</td>
<td align="center">
<a href="https://github.com/FeliciaJiangBio/3DisoDeepPF">
<img src="https://github.com/user-attachments/assets/80d606fc-bc19-446c-b726-bb0d8e69b42c" alt="3DisoDeepPF">
<br><b>3DisoDeepPF</b>
</a>
</td>
</tr>
</table>
</div>

### Workflow Overview

<img src="https://github.com/user-attachments/assets/d0837471-63ab-4c45-a08f-7454ffe03624" alt="Workflow Overview Diagram">

The workflow orchestrates the comprehensive analysis from long-read RNA-seq data to the prediction of protein isoform structures and the construction of the structural similarity network.

### How to Use This Repository and Quick Start

The core methodology involves retaining master transcriptome ORFs only if validated by Ribo-seq, ensuring their translation. ORFs are predicted using TransDecoder (BLASTP, HMMER, and machine learning), filtered for quality, and then the longest sequence per isoform undergoes AlphaFold-2.3 structure prediction. TMalign calculates pairwise isoform similarities, forming a "protein universe," annotated with functional domains and GO terms from UniProtKB. This network pinpoints cancer-specific isoforms for subtype-specific therapeutic screening and validation.

#### Repository Organization

This repository is organized into distinct modules for data processing, structural prediction, and network construction. The workflow is primarily written in **Python and Bash scripting**, allowing for flexible and scalable execution. We encourage community contributions and feedback to further enhance this resource.

#### Quick Start Guide

This quick start guide assumes you are running Python version 3.10 and CUDA version 11.6.

##### Prerequisites

1. **AlphaFold2.3**: Download and install from [AlphaFold2.3 Link]
2. **PacBio tools**: Installation instructions [PacBio Link]
3. **TransDecoder**: Installation instructions [TransDecoder Link]
4. **TALON**: Installation instructions [TALON Link]
5. **RSEM**: Installation instructions [RSEM Link]
6. **STAR**: Installation instructions [STAR Link]
7. **ProteinVec**: Installation instructions [ProteinVec Link]
8. **DeepLoc**: Installation instructions [DeepLoc Link]
9. **Autodock**: Installation instructions [Autodock Link]
10. **Foldseek**: Installation instructions [Foldseek Link]
11. **ColabFold**: Installation instructions [ColabFold Link]

##### Installation Steps

<div class="code-block">
<pre><code># Create conda environment
conda create -n 3disotf python=3.10
conda activate 3disotf

# Clone the main repository (choose one)
git clone https://github.com/CityUHK-CompBio/3Diso-TransFold
# OR
git clone https://github.com/TJiangBio/3DisoGalaxy

# Navigate into the cloned directory
cd 3DisoGalaxy
</code></pre>
</div>

##### Running the Pipeline

<div class="code-block">
<pre><code># Execute the main pipeline script
bash main.sh
</code></pre>
</div>

### Documentation and Workflow Details

The pipeline comes with detailed documentation available in the Wiki section of the repository, covering:

- Third-party tools and their integration
- Input parameters and file formats
- Output files and their interpretation
- Comprehensive descriptions of pipeline processes
- Usage Vignettes

### Contributors

- Felicia Jiang
- Justin
- Hao Hao

This is a joint project between collaborating organizations.

### Acknowledgements

We extend our sincere gratitude to **Cosmograph: GPU-accelerated Force Graph Layout and Rendering** (Rokotyan, N., Stukova, O., Kolmakova D. & Ovsyannikov, D., 2022) for providing an intuitive and efficient platform for visualizing protein similarity networks, which was instrumental in exploring complex topologies and cluster associations within our study. The clear presentation capabilities of Cosmograph were crucial for interpreting relationships between protein structures and functions. We are also deeply thankful to **Mol\*** for its advanced capabilities in visualizing protein structures in three dimensions. This tool enabled precise exploration of structural details and interactions, offering critical insights into protein similarity mechanisms and their biological relevance for metastasis prediction. Both visualization tools were invaluable for data interpretation and for presenting our findings clearly and accessibly.

### Citation

If you utilize this pipeline or the generated data in your research, please cite our forthcoming publication:

<div class="code-block">
<pre><code>Jiang, F., et al. (2025). The Structural Code of Breast Cancer Heterogeneity: Alternative Splicing-driven Proteoform Variation and Functional Diversification. [Journal Name] Manuscript: [Paper Title]
</code></pre>
</div>

Further DOI information for specific datasets will be provided here upon publication:

| DOI | Description |
|-----|-------------|
| [![DOI](badge_url)](doi_link) | Contains... |
| [![DOI](badge_url)](doi_link) | Contains... |

</div>
