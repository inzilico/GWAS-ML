# Genome-Wide Association Studies of Ischemic Stroke Based on Interpretable Machine Learning


## Abstract
Despite a few dozens of risk genetic loci of ischemic stroke (IS) are known, the genetic bases of this disease remain unexplored. In this research we present the results of genome-wide association studies (GWAS) based on classical statistical testing and machine learning algorithms (logistic regression, decision tree library XGBoost, and interpretable neuronal network TabNet). To build a consensus on the results obtained by different techniques, the Pareto-Optimal solution was proposed and applied. These methods were applied to a real genotypic data of sick and healthy individuals of European ancestry obtained from the Database of Genotypes and Phenotypes (5581 individuals, 883749 Single Nucleotide Polymorphisms). Finally 131 genes were identified as candidates for association with the onset of IS. UBQLN1, TRPS1, and MUSK  were described previously as being associated with the course of IS in model animals. ACOT11 taking part in metabolism of fatty acids was shown for the first time to be associated with IS. The genes identified were compared with genes from the Illuminating Druggable Genome project. The product of GPR26 representing G-coupled protein receptor can be considered as therapeutic target for stroke prevention. The approaches presented in this research can be used to reprocess GWAS datasets of other diseases. 
    
# Overview

## Code sections
- ```Manhattan_Plot.ipynb``` contains the code for generating manhattan plot used in paper (figure 1)
- ```LR_plot.ipynb``` contains the code for generating F1 loss dynamic used in paper (figure 2)  