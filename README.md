
# Telco Customer Churn Analysis Using EDA and Deep Learning

## Project Overview
This project performs Exploratory Data Analysis (EDA), statistical analysis,
data visualization, and Deep Learning to investigate customer churn.

## Dataset
- Source: Kaggle Telco Customer Churn
- URL: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- Records: 7,043
- Columns: 21
- Target variable: Churn

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Plotly
- Scikit-learn
- TensorFlow/Keras
- Google Colab

## Project Workflow
1. Dataset loading and understanding
2. Data cleaning and preprocessing
3. Statistical analysis and EDA visualizations
4. Train, validation, and test split
5. MLP Deep Learning model training
6. Hyperparameter comparison
7. Model evaluation and feature importance

## Final Test Results
- Accuracy: 79.94%
- Precision: 66.35%
- Recall: 49.82%
- F1-score: 56.91%
- ROC-AUC: 0.8412

## Key Findings
Tenure and contract type were the two most influential features
in the permutation importance analysis.

The month-to-month contract group had a churn rate of 42.71%,
while the two-year contract group had a churn rate of 2.83%.

## Files
- EDA_Telco_Customer_Churn.ipynb: Project code and analysis
- EDA_Telco_Customer_Churn_Report.pdf: Complete assignment report
- dataset_source.txt: Dataset source and download instructions

## How to Run
Open the notebook in Google Colab and execute the cells in order.
The notebook loads the dataset, performs EDA, trains the model,
and evaluates its performance.

## Limitations
The model achieved 49.82% recall for the churn class, so further
improvement is required to identify more customers who leave.



## Dataset Source

Dataset: Telco Customer Churn

Download the dataset from [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

The dataset contains customer information, subscribed services, contract details, billing information, and the churn target variable.

