# Urban Infrastructure Failure Prediction

This project applies machine learning techniques to predict infrastructure failure in urban environments.

## Objective
To classify whether a city block will experience infrastructure failure using environmental and structural features.

## Methodology
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Train/Validation/Test split (60/20/20)
- Feature scaling and encoding
- Models used:
  - Logistic Regression
  - Decision Tree
  - Neural Network

## Evaluation
ROC-AUC was used due to moderate class imbalance (63% no-failure / 37% failure), as it better reflects the model’s ability to distinguish between classes than accuracy.

## Key Insight
Environmental stress factors (e.g. moisture and debris) and infrastructure age are the strongest predictors of failure risk.

## Files
- `Urban_Poster.pdf` – Final poster 
- `Urban_Notebook.ipynb` – Full modelling process

