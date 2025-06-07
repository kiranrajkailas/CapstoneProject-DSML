# CapstoneProject-DSML
Project objective:
  The goal of this project is to develop a machine learning model that accurately predicts the critical temperature of materials based on their elemental and physical properties. 
  By analyzing a comprehensive dataset of engineered features such as atomic mass, electron affinity, and thermal conductivity, the model aims to identify patterns that govern superconducting behavior and provide insights into material design for advanced technological applications. 
------------------------------------------------------------------------------------------
Model type: Regression
Topic: Science
------------------------------------------------------------------------------------------
# Detailed Summary:
### Superconductivity Critical Temperature Prediction

This capstone project applies machine learning techniques to predict the **critical temperature (Tc)** of superconductors based on material composition features. The dataset originates from a curated version of the **SuperCon database**, preprocessed and structured with 81 numeric descriptors for ML modeling.

#### Dataset
- Source: SuperCon (NIMS, Japan), processed as 'train.csv' (81 features)
- Target variable: 'critical_temp'
- Features derived using atomic and elemental properties (e.g., atomic radius, valence, electronegativity)

#### Project Workflow
- Data loading and inspection
- Exploratory data analysis and preprocessing
- Feature and target split
- Train-test split using 'train_test_split'
- Model training:
  - XGBoost Regressor
  - Random Forest Regressor
- Model evaluation:
  - Metrics: RMSE, R² Score
  - Visualization: Actual vs. Predicted plots, Residual analysis
