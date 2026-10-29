# Medical Insurance Cost Prediction Using Supervised Machine Learning

## Objective
Predict medical insurance charges using demographic and lifestyle features from the Kaggle Medical Insurance dataset.

## Algorithms
- Linear Regression
- Generalized Linear Model (Gamma GLM with log link)
- Support Vector Regression (RBF kernel)

## Dataset
Download the Kaggle Medical Insurance dataset and place the CSV file named `insurance.csv` in the same folder as the notebook. In Google Colab, the notebook prompts you to upload the CSV.

Expected columns: `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`.

## Files
- `medical_insurance_cost_prediction.ipynb` — complete notebook with data exploration, preprocessing, model training, evaluation, and plots.
- `requirements.txt` — required Python packages.
- `report.md` — short project report template with objective, methodology, and interpretation guidance.

## Run in Google Colab
1. Upload the notebook to Google Colab.
2. Run the cells in order.
3. Upload `insurance.csv` when prompted.
4. Review the evaluation table and plots.

## Metrics
MSE, RMSE, MAE, and R². Lower error metrics are better; higher R² is better.

## Notes
The notebook uses one-hot encoding for categorical variables and fits preprocessing only on the training set. Gamma GLM requires strictly positive target values. Model performance can vary by split and configuration.
