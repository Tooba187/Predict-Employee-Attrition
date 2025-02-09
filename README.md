# Predict-Employee-Attrition
# Employee Attrition Prediction

## Overview
This project predicts employee attrition using the IBM HR Analytics dataset. It includes EDA, classification models, and actionable insights for retention strategies.

## Project Structure
- `data/`: Contains `WA_Fn-UseC_-HR-Employee-Attrition.csv`.
- `notebooks/`:  
  - `1_EDA.ipynb`: Exploratory data analysis and visualizations.  
  - `2_Model_Training.ipynb`: Trains Random Forest and Logistic Regression models.  
  - `3_SHAP_Analysis.ipynb`: Explains model predictions using SHAP.  
- `reports/`:  
  - `attrition_analysis.pdf`: Detailed report with findings and strategies.  

## Dependencies
- Python 3.8+
- Libraries: pandas, scikit-learn, matplotlib, seaborn, SHAP.

## Usage
1. Install dependencies:  
   ```bash
   pip install pandas scikit-learn matplotlib seaborn shap
2. Run Jupyter notebooks in order (1 → 2 → 3).
Key Results
Top Attrition Drivers: Overtime, low income, job dissatisfaction.

Model Performance: Random Forest (AUC: 0.91).

Recommendations: Flexible hours, salary adjustments, mentorship programs.

---

**attrition_analysis.pdf Contents (Summary)**  
- **Introduction**: Objective and dataset description.  
- **EDA Visuals**: Attrition rates by department, income distribution, correlation heatmap.  
- **Model Metrics**: Accuracy, recall, and AUC comparisons.  
- **SHAP Analysis**: Feature importance plots and example predictions.  
- **Retention Strategies**: 4 actionable recommendations for HR.  
