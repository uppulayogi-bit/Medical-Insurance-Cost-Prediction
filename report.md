# Project Report: Medical Insurance Cost Prediction Using Supervised Machine Learning

## Objective
Predict medical insurance charges using demographic and lifestyle features.

## Dataset Description
The Kaggle Medical Insurance dataset contains age, sex, BMI, number of children, smoking status, residential region, and medical insurance charges. The target variable is `charges`.

## Methodology
1. Load and inspect the dataset.
2. Check missing values and explore distributions and relationships with visualizations.
3. Separate input features from the target variable.
4. Split the dataset into training and test sets (80%/20%).
5. Impute missing values, scale numerical features, and one-hot encode categorical features.
6. Train Linear Regression, Gamma GLM, and Support Vector Regression models.
7. Evaluate the models using MSE, RMSE, MAE, and R².
8. Compare actual and predicted charges and interpret the results.

## Results
Run the notebook and copy the final metrics table and plots into this section. Do not enter expected scores before running the notebook.

## Conclusion
Discuss which model performs best on the held-out test set and whether its error metrics are acceptable for this dataset. Note that performance depends on the split and model configuration.

## Limitations
The dataset is observational and based on a particular population. The model is intended for educational use and should not be used as an official insurance pricing tool.
