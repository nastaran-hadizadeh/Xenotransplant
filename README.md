# Project description



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
│   │   ├── Timecourse analyses/
│   ├── Gene set scoring/
│   │   ├── Cell_Death_pathways/
│   │   ├── Metabolic pathways/
│   │   ├── OSM_pathway/
│   │   └── MP polarization/
│   │   └── Cell_cycle_scoring/
│   ├── Cellchat/
│   │   ├── Rejection_vs_3month/
│   │   └── 6month_vs_3month/
│   ├── Pseudobulk analysis/
│   │   ├── Rejection_vs_3month/
│   │   ├── 6month_vs_3month/
│   │   └── PCMV_vs_3month/
│   ├── EdgeR/
│   │   ├── REF_control/
│   │   └── REF_3month/
│   └── Functional enrichment analysis/
│   └── Further_analyses/
└── Clinical/
    ├── Global object annotation/
    ├── Subclustering/
    ├── Pseudobulk analysis/
    ├── Wilcox/
    ├── Checking_genes/
    ├── PCMV_expression/
    └── Functional enrichment analysis/
