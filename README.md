# Customer Churn Prediction

A machine learning project that predicts telecom customer churn using a Random Forest Classifier.

## Project Overview

Customer churn prediction helps businesses identify customers who are likely to leave their service. In this project, the Telco Customer Churn dataset is analyzed, visualized, and used to train a machine learning model for churn prediction.

## Dataset

**Dataset:** Telco Customer Churn Dataset

Source: Kaggle - Telco Customer Churn Dataset

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Exploratory Data Analysis (EDA)

The project includes:

* Churn Distribution Analysis
* Correlation Heatmap
* Tenure vs Churn Analysis
* Monthly Charges vs Churn Analysis

## Machine Learning Model

Algorithm Used:

* Random Forest Classifier

Evaluation Metrics:

* Accuracy
* Classification Report
* Confusion Matrix
* ROC Curve
* AUC Score

## Results

* Model Accuracy: 78.54%
* Customer tenure is strongly related to churn.
* Customers with higher monthly charges are more likely to churn.
* Contract type and service usage significantly influence churn behavior.

## Project Structure

```text
churn_project/
│
├── data/
├── images/
├── churn_analysis.ipynb
├── README.md
└── .gitignore
```

## How to Run

1. Clone the repository
2. Create and activate a virtual environment
3. Install dependencies
4. Download the dataset from Kaggle
5. Place the dataset inside the data folder as `churn.csv`
6. Run `churn_analysis.ipynb`

## Author

Umang
