# TumorAnalyzer

This project uses the 'Human Breast Cancer: Whole Transcriptome Analysis' dataset provided by 10x Genomics.
Link: https://www.10xgenomics.com/datasets/human-breast-cancer-whole-transcriptome-analysis-1-standard-1-2-0

For image CNN download "Image (TIFF)" from Input files and "tissue_positions_list.csv" from "Spatial imaging data" from Output and supplemental files.

For Genomic Pipeline download "Feature / barcode matrix HDF5 (filtered)" from Output and supplemental files.
Tasks: QC filtering (Scanpy) and latent feature extraction using a PyTorch Transformer/VAE.
Goal: Generate gene embeddings for multi-omic fusion.
