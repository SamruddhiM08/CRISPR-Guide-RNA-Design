# CRISPR Guide RNA Design for EGFP Gene

## Project Overview
This project focuses on the computational design and analysis of CRISPR guide RNAs targeting the Enhanced Green Fluorescent Protein (EGFP) gene using CRISPR-Cas9.

---

## Objective
To identify efficient and specific guide RNAs for targeting the EGFP gene using bioinformatics tools.

---

## Tools Used
- NCBI
- SnapGene Viewer
- CHOPCHOP
- Microsoft Excel

---

# Methodology

## Step 1 — Sequence Retrieval
The EGFP nucleotide sequence was retrieved from the NCBI database in FASTA format.

### Figure
![NCBI Sequence] <img width="1348" height="629" alt="ncbi_fasta" src="https://github.com/user-attachments/assets/bd7aa7a1-227f-408a-929d-a6e82ecfe54d" />



---

## Step 2 — FASTA Sequence Preparation
The DNA sequence was saved in FASTA format and imported into SnapGene Viewer for visualization and sequence inspection.

---

## Step 3 — PAM Site Identification
Potential Cas9 PAM regions (NGG motifs) were identified using SnapGene Viewer.

### Figure
![PAM Analysis](figures/snapgene_pam_analysis.png)

---

## Step 4 — Guide RNA Design
The EGFP sequence was uploaded into CHOPCHOP for CRISPR guide RNA prediction using the Cas9 system.

Parameters:
- Cas System: Cas9
- PAM: NGG
- Target Type: Knockout

### Figure
![CHOPCHOP Results](figures/chopchop_results.png)

---

## Step 5 — Guide Selection
Guide RNAs were filtered based on:
- High efficiency score
- MM1 = 0
- Low MM2/MM3 values
- Suitable GC content

Selected guides are provided in:
`tables/guide_selection_table.xlsx`

---

## Step 6 — Guide Visualization
The selected guide RNA and PAM region were visualized in SnapGene Viewer.

### Figure
![Guide Visualization](figures/cas9_guide_visualization.png)

---

## Step 7 — Off-target Validation
Selected guides were validated using CRISPOR to analyze specificity and potential off-target effects.

### Figure
![CRISPOR Validation](figures/crispor_validation.png)

---

# Results
Three high-quality guide RNAs were identified for CRISPR-Cas9 targeting of the EGFP gene.

---

# Conclusion
This project successfully identified efficient CRISPR guide RNAs targeting the EGFP gene using computational bioinformatics tools.

---
