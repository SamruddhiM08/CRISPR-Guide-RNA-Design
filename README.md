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
![PAM Analysis]

---

## Step 4 — Guide RNA Design
The EGFP sequence was uploaded into CHOPCHOP for CRISPR guide RNA prediction using the Cas9 system.

Parameters:
- Cas System: Cas9
- PAM: NGG
- Target Type: Knockout

### Figure
![CHOPCHOP Results](<img width="1352" height="632" alt="chopchop_results" src="https://github.com/user-attachments/assets/69363c2c-164f-4309-b138-66365a6d462e" />
)

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
![Guide Visualization](<img width="1365" height="721" alt="snapgene_pam_analysis png" src="https://github.com/user-attachments/assets/13e9c27b-3c38-4c8c-aecb-25305aa4ff91" />
)

---

## Step 7 — Off-target Validation
Selected guides were validated using CHOPCHOP to analyze specificity and potential off-target effects.

### Figure
![CHOPCHOP Validation](<img width="1365" height="716" alt="guide1_pam_region" src="https://github.com/user-attachments/assets/472e533c-1bcc-490e-8a96-517979b74a92" />
)

---

# Results
Three high-quality guide RNAs were identified for CRISPR-Cas9 targeting of the EGFP gene.

---

# Conclusion
This project successfully identified efficient CRISPR guide RNAs targeting the EGFP gene using computational bioinformatics tools.

---
