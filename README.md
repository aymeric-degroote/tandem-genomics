# tandem-genomics


Expected folder hierarchy:
```
.
|-- src
|   |-- notebook-multivelo.ipynb
|   |-- notebook-pathways.ipynb
|   |-- notebook-preprocess.ipynb
|   `-- notebook-tandem.ipynb
|-- plots
`-- data
    |-- outs
    |   |-- analysis
    |   |   `-- feature_linkage
    |   |       `-- feature_linkage.bedpe
    |   |-- filtered_feature_bc_matrix
    |   |   |-- barcodes.tsv.gz
    |   |   |-- features.tsv.gz
    |   |   `-- matrix.mtx.gz
    |   `-- peak_annotation.tsv
    |-- results
    |   |-- adata_atac_mouse_brain.h5ad
    |   |-- adata_rna_mouse_brain_analyzed.h5ad
    |   |-- adata_rna_mouse_brain.h5ad
    |   |-- GSEA_overlap_result_0.tsv
    |   |-- GSEA_overlap_result_1.tsv
    |   |-- GSEA_overlap_rna_0.tsv
    |   `-- GSEA_overlap_rna_1.tsv
    |-- seurat_wnn
    |   |-- nn_cells.txt
    |   |-- nn_dist.txt
    |   `-- nn_idx.txt
    |-- velocyto
    |   `-- 10X_multiome_mouse_brain.loom
    |-- cell_annotations.tsv
    `-- filtered_cells.txt
```

By Aymeric Degroote (@aymeric-degroote) & Matthieu Dagommer (@MatDagommer)


Code for a project for the course 'BMEN 4480 Statistical Machine Learning for Genomics' hold by Elham Azizi, Department of Biomedical Engineering, Columbia University.

Why tandem? Because CellRank and MultiVelo work as a tandem!  
Also, "Velo" means "bicycle" in French so "MultiVelo" naturally designates a tandem...
