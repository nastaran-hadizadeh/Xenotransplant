# Project description

> [!IMPORTANT]
> **Terminology Mapping**
> Some group names were changed in the manuscript compared to the codes. In the codebases, the following group names correspond to the names used in the manuscript:
> * **Standard protocol** = 3month protocol
> * **Extended protocol** = 6month protocol
> * **PCMV** = PCMV/PRV
> 
> All other names remain unchanged.

---

# Organization of repository

This repository is organized into **Preclinical** and **Clinical** analyses, with consistent subfolders for annotation, subclustering, differential expression, and downstream interpretation.

## Repository tree

```text
Xenotransplant
.
├── Preclinical/
│   ├── Global object annotation/
│   │   ├── Mapping/
│   │   └── Solo/
│   ├── Subclustering/
│   │   ├── Pig_myeloids/
│   │   ├── Baboon_myeloids/
│   │   ├── Pig_lymphoids/
│   │   ├── Baboon_lymphoids/
│   │   ├── Cardiomyocytes (CM)/
│   │   ├── Endothelial cells (EC)/
│   │   ├── Fibroblasts (FB)/
│   │   └── Timecourse analyses/
│   ├── Gene set scoring/
│   │   ├── Cell_Death_pathways/
│   │   ├── Metabolic pathways/
│   │   ├── OSM_pathway/
│   │   ├── MP polarization/
│   │   └── Cell_cycle_scoring/
│   ├── Cellchat/
│   │   ├── Rejection_vs_3month/
│   │   └── 6month_vs_3month/
│   ├── CLR/
│   │   ├── Ref_control_celltype/
│   │   ├── Ref_3month_celltype/
│   │   └── Ref_3month_cellstate/
│   │       ├── CM/
│   │       ├── FB/
│   │       ├── Vasc_EC/
│   │       ├── Res_Immune/
│   │       ├── Lymph_papio/
│   │       └── Mye_papio/
│   ├── Pseudobulk analysis/
│   │   ├── Rejection_vs_3month/
│   │   ├── 6month_vs_3month/
│   │   └── PCMV_vs_3month/
│   ├── EdgeR/
│   ├── Proteomics/
│   ├── Functional enrichment analysis/
│   └── Further_analyses/
└── Clinical/
    ├── Global object annotation/
    ├── Subclustering/
    ├── Pseudobulk analysis/
    ├── Wilcox/
    ├── Checking_genes/
    ├── PCMV_expression/
    └── Functional enrichment analysis/
