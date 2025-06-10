# Parse + 10x Single-Cell RNA-seq Integration — Same Tissue Type

This project integrates single-cell RNA-seq data generated from the same tissue using two different platforms: **Parse Biosciences** and **10x Genomics**. The objective is to harmonize datasets across platforms, remove batch effects, and perform unified clustering and marker identification.

---

## 📘 Project Overview

Two single-cell datasets were generated from the same tissue using different technologies:
- **Parse Biosciences (split-pool barcoding)**
- **10x Genomics (droplet-based sequencing)**

To enable integrated analysis, I processed and filtered each dataset independently, identified shared genes, and then performed integration to eliminate platform-driven batch effects. Unified clustering and marker discovery were carried out to characterize shared cell populations across platforms.

---

## 📊 Analysis Task

### **Task: Cross-Platform Integration and Cell Type Characterization**
- Read and create Seurat objects for Parse and 10x datasets individually
- Perform initial filtering and quality control on each
- Identify common genes across both datasets
- Integrate Parse and 10x Seurat objects using Seurat’s integration workflow
- Normalize, scale, and run PCA on integrated object
- Perform clustering and UMAP visualization
- Identify cluster markers for biological interpretation

---


# 💡 Notes

- Raw data is not publicly available due to client ownership and confidentiality.
- Some example outputs plots are organized by task in the `output/` folder.
- This project is designed for both reproducibility and clarity.

---

## 📬 Contact

*Author:* Nasim Rahmatpour 
*Email:* nasimrahmatpour1@gmail.com 
*GitHub:* (https://github.com/nasimbio)



