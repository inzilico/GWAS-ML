# Genome-Wide Association Studies of Ischemic Stroke Based on Interpretable Machine Learning


## Description
The repo contains the scripts applied for data processing presented in the article:

Nikolić S., Ignatov D., Khvorykh G., Limborska S., and Khrunin A., Genome-Wide Association Studies of Ischemic Stroke Based on Interpretable Machine Learning, PeerJ Computer Science, 2024 (in press).
 
    
# Overview

## Requirements
- python >= 3.6
- numpy >= 1.23.5
- matplotlib >= 3.7.2
- sklearn >= 1.1.3
- catboost >= 1.2
- lightgbm >= 3.3.5
- xgboost >= 1.7.6
- pandas >= 2.0.3
- json >= 2.0.9
- IPython >= 8.14.0
- scipy >= 1.11.1
- bioinfokit >= 2.1.3 

## Code sections
- ```Manhattan_Plot.ipynb``` contains the code for generating manhattan plot used in paper (figure 1)
- ```LR_plot.ipynb``` contains the code for generating F1 loss dynamic used in paper (figure 2) 
- ```pareto_plots.ipynb``` contains the code for obtaining pareto plots and training some models