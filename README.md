## Metallic Glass Forming Ability Prediction

### Overview
This repository contains code and data for predicting the critical casting diameter (Dmax), a crucial parameter defining the glass-forming ability of metallic glasses. We utilize regression modeling techniques, specifically Extra Trees Regression, to predict Dmax based on experimental data.

### Methodology
- **Feature Augmentation**: To enhance model performance, we implemented feature augmentation techniques. This involved introducing new features such as temperature functions and extracting composition information from the alloys. Additionally, we utilized the presence of certain metals to create boundaries between particular sets of Dmax.
  
- **Regression Modeling**: The predictive model is built using Extra Trees Regression, a robust ensemble learning technique. We trained the model on experimental data, aiming to accurately predict Dmax based on various input features.

### Results
The regression model achieved an impressive R2 score of 0.8669, indicating strong predictive performance and a good fit to the experimental data. 

### Dependencies
- Python 3.x
- NumPy
- Pandas
- scikit-learn

### Authors
- [Prakhar Tripathi]
