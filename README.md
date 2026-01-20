# Pickles-Asia
Physical Assesment

# Section A
Goal - To predict vehicle sale prices (Sold_Amount) given two data set DatiumTrain & DatiumTest in rpt format.

## Thought Process: Vehicle Sale Price Prediction Report

This plan outlines the steps to build, document, and track a predictive model for vehicle sale prices (`Sold_Amount`) using the provided `.rpt` dataset. The process will be fully documented in a Jupyter Notebook, with code, analysis, and experiment tracking.

### Steps
1. **Data Understanding & Cleaning**
   - Load data from `Data/DatiumTrain.rpt` using pandas as Dataframe.
   - Explore data: check for missing values, outliers, and data types.
   - Highlight errors, inconsistencies, and concerns in the data.

2. **Feature Selection & Engineering**
   - Identify relevant features, excluding forbidden fields (`AvgWholesale`, `AvgRetail`, `GoodWholesale`, `GoodRetail`, `TradeMin`, `TradeMax`, `PrivateMax`).
   - Engineer new features if beneficial (e.g., age from `YearGroup`, `Sold_Date`).
   - Encode categorical variables (e.g., one-hot, target, or ordinal encoding).

3. **Model Experimentation**
   - Try various models (e.g., linear regression, tree-based, boosting, or other libraries).
   - Experiment with different feature encoding and preprocessing pipelines.
   - Use cross-validation and train/test splits for robust evaluation.

4. **Evaluation & Diagnostics**
   - Evaluate models using metrics like RMSE, MAE, and R².
   - Analyze residuals and feature importances to diagnose underperformance.
   - Document findings and model limitations.

5. **Model Training Class**
   - Implement a reusable Python class for model training, validation, and prediction.
   - Include methods for preprocessing, fitting, and evaluation.

6. **Experiment Tracking**
   - Integrate MLFlow or similar tool for logging experiments, parameters, and metrics.
   - Save experiment logs and results for reproducibility.

7. **Documentation & Reporting**
   - Document the entire process, decisions, and results in the notebook.
   - Provide a README with setup and execution instructions.

### Further Considerations
1. Should we prioritize model interpretability or predictive accuracy?
2. Are there any business constraints or requirements for model deployment?
3. Would you like to include visualizations for data exploration and model diagnostics?
