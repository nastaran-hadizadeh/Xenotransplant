# Project discription



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
│   ├── Gene set scoring/
│   │   ├── Cell death pathways/
│   │   ├── Metabolic pathways/
│   │   ├── OSM signaling/
│   │   └── MP polarization/
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
└── Clinical/
    ├── Global object annotation/
    ├── Subclustering/
    ├── Pseudobulk analysis/
    ├── Wilcox/
    └── Functional enrichment analysis/
