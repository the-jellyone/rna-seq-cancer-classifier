# rna-seq-cancer-classifier
End-to-end pipeline for predicting cancer types from high-dimensional gene expression data using PCA and ensemble learning.

##Project Overview
This project demonstrates classification of five cancer types (BRCA, COAD, KIRC, LUAD, PRAD) using RNA-Seq gene expression data from the UCI Pan-Cancer dataset. Dimensionality reduction via PCA and ensemble models (Random Forest, XGBoost) were applied to handle the high-dimensional feature space.

##Dataset
- Source: [UCI Machine Learning Repository – Gene Expression Cancer RNA-Seq Data]([https://archive.ics.uci.edu/ml/datasets/Gene+Expression+Cance)](https://archive.ics.uci.edu/dataset/401/gene+expression+cancer+rna+seq)
- 881 samples × 20,531 genes
- Five cancer classes: BRCA, COAD, KIRC, LUAD, PRAD

##Results
- XGBoost achieved 98% accuracy ,Random forest 96%.
- PCA reduced 20k features to 50 principal components.
- Class-wise evaluation demonstrates strong predictive power  on most cancer types.
