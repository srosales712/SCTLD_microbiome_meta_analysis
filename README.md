# 🦠 SCTLD Microbiome Meta-Analysis

This repository contains the data and code for the meta-analysis conducted in:

> **“A meta‑analysis of the stony coral tissue loss disease microbiome finds key bacteria in unaffected and lesion tissue in diseased colonies”**  
> S. M. Rosales et al. (2025), *ISME Communications* :contentReference[https://doi.org/10.1038/s43705-023-00220-0]

---

## 📚 Study Highlights

- 🔎 Largest meta-analysis to date on the microbiome of **Stony Coral Tissue Loss Disease (SCTLD)**  
- Examined 17 studies (16 SCTLD + 1 Rapid Tissue Loss)  
- Compared microbiomes in:
  - Apparently Healthy (AH) corals across different disease zones (vulnerable, endemic, epidemic)
  - Diseased coral tissue – Diseased Unaffected (DU) vs. Disease Lesion (DL)
- 🧬 Key findings:
  - AH corals in endemic/epidemic zones had bacterial changes that might indicate compromised health or resistance  
  - DU samples: dominated by **Flavobacteriales** and **Synechococcales**  
  - DL samples: enriched in **Rhodobacterales** and **Peptostreptococcales–Tissierellales**, with the latter potentially involved in tissue loss via phospholipase C/α-toxin pathways.
---

## 📁 Repository Structure

- **`Data/`**  
  - Compiled ASV tables, taxonomy assignments, and metadata across all included studies.

- **`Notebooks/`**  
  - Jupyter notebooks (R/Python) for data cleaning, processing, and meta-analysis workflows.

- **`DADA2_output`**
  -   Notebooks of Qiime2 analysis of each study and then merged.

---

- **`## 🛠️ Reproducing the Analysis

1. **Clone the repo**  
   ```bash
   git clone https://github.com/srosales712/SCTLD_microbiome_meta_analysis.git
   cd SCTLD_microbiome_meta_analysis
