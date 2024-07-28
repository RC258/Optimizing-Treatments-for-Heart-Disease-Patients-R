# Introduction
This repository provides two R scripts in R-markdown format. The datasets is obtained from [Kaggle](https://www.kaggle.com/datasets/kingabzpro/heart-disease-patients/data).

These scripts leverage multiple machine learning techniques to optimize treatment strategies for heart patients based on their specific characteristics: Clustering and discriminant analysis are used to group patients by these characteristics. Cross-validation helps train the model and ensures that the regularization methods (Lasso, Adaptive Lasso) successfully identify factors affecting maximum heart rate. 

These selected factors contribute to establishing an optimal heart disease monitoring model, which reduces disease screening pressures and lowers monitoring costs for specific patient groups.

# Remarks
- Considering data ethics and privacy, patient information has been anonymized.
- Some of the packages used are not included by default in RStudio and require manual installation.
- The current dataset contains only 303 patients, which may lead to potential overestimation. Expanding the dataset is required.
 
