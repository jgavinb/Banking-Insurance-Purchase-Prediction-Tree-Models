# Banking Insurance Purchase Prediction: Tree Models

## Description  
This project predicts customer purchases of a variable annuity insurance product for a commercial bank using tree-based machine learning models. The solution includes data imputation, hyperparameter tuning, and model evaluation, demonstrating proficiency in end-to-end predictive analytics.  

**Tools Used**  
- **R**: `randomForest`, `xgboost`, `caret`, `dplyr`, `ROCit`  
- **Workflow**: RMarkdown for reproducible analysis  

## Key Features  
- Imputed missing data using **median/mode** for continuous/categorical variables.  
- Built and tuned **Random Forest** and **XGBoost** models to optimize predictive performance.  
- Evaluated models using **AUC-ROC** and identified key drivers of insurance purchases.  
- Automated variable importance reporting and visualization.  

## Results  
- Achieved **AUC-ROC of 0.89** with the tuned XGBoost model.  
- Random Forest identified **account age (ACCTAGE)** and **checking balances (DDABAL)** as top predictors.  
- Streamlined model deployment-ready code with clear documentation. 
