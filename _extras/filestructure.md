---
layout: page
title: Folder Structure and Layout
permalink: /filestructure/index.html
---

```bash
.
└── Viromics2025_workspace
    ├── 1.1_QC
    │   ├── 10_nanoplot
    │   │   └── virome
    │   └── 20_chopper
    ├── 1.2_assembly
    │   ├── 10_assembly_flye
    │   │   ├── 00-assembly
    │   │   ├── 10-consensus
    │   │   ├── 20-repeat
    │   │   ├── 30-contigger
    │   │   └── 40-polishing
    │   ├── 20_vclust
    │   └── 30_quast
    │       └── assembly
    ├── 1.3_virus_identification
    │   ├── 10_jaeger
    │   │   └── assembly
    │   ├── 20_checkv
    │   │   └── tmp
    │   └── 30_filter_contigs
    ├── 1.4_gene_annotation
    │   ├── 10_pharokka
    │   │   └── results
    │   └── 20_selected_contig
    ├── 1.5_taxonomy
    │   ├── 10_terL_tree
    │   └── 20_vcontact_results
    │       └── exports
    ├── 2.1_host_prediction
    │   └── 10_rafah
    │       └── split_contigs
    ├── data
    │   ├── alignments
    │   │   └── phylogenetic_alignments
    │   └── sequences
    ├── py3env
    │   ├── bin
    │   ├── ete3
    │   │   └── tools
    │   ├── include
    │   ├── lib
    │   │   └── python3.9
    │   ├── lib64 -> lib
    │   └── share
    │       └── man
    └── python_scripts
```
