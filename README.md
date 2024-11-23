# Customer_Churn_Prediction

This repository contains a comprehensive project on Customer Churn Analysis and Prediction using data science and machine learning techniques. The goal of this project is to understand the factors influencing customer churn and to build a predictive model to help businesses retain customers effectively.
I will analyze the content of your uploaded file to draft a README.md file for your project based on the roadmap you provided. Let me first inspect the content of the notebook.

The notebook contains extensive content with sections likely related to data cleaning, exploratory data analysis (EDA), and machine learning modeling. I'll extract key insights from it to generate a well-structured `README.md` file.

Let me summarize the main sections of the notebook and prepare the README file accordingly.

The notebook includes detailed steps for data cleaning, exploratory data analysis (EDA), and model training for customer churn prediction. It uses the **Telco Customer Churn** dataset from Kaggle. Key processes involve data extraction, cleaning, feature engineering, and machine learning modeling.

Here's the draft `README.md` file based on this analysis:

---

# Customer Churn Prediction with Data Cleaning, EDA, and Machine Learning

## Project Description

This project aims to predict customer churn using the **Telco Customer Churn** dataset. By analyzing customer behavior and service usage, the project identifies patterns that lead to churn. This insight is valuable for businesses to improve retention strategies.

Key steps include:

- Cleaning raw data to address missing values and inconsistencies.
- Performing EDA to understand customer trends and behavior.
- Training machine learning models to predict churn probability.

## Dataset

The dataset contains customer information, including demographic, service, and billing details. It is sourced from Kaggle.

### Features

- **CustomerID**: Unique customer identifier.
- **Services**: Subscriptions like phone, internet, security, and streaming services.
- **Billing**: Monthly charges, total charges, and Trenure.
- **Demographics**: Gender, senior citizen status, partner, and dependent details.
- **Target Variable**: `Churn` (Binary: Yes/No).

### Data Summary

- **Size**: Approximately 7,000 rows with 21 columns.
- **Source**: [Kaggle](https://www.kaggle.com/datasets/samkayyali/wa-fnusec-telcocustomerchurn).

## Project Workflow

### 1. Data Cleaning

- Extracted data from a ZIP file.
- Handled missing and inconsistent values.
- Standardized column names and data types.

### 2. Exploratory Data Analysis (EDA)

- Visualized customer trends by demographics, services, and billing patterns.
- Identified features influencing churn using correlation heatmaps and pair plots.

### 3. Feature Engineering

- Encoded categorical variables.
- Scaled numerical features for model compatibility.

### 4. Machine Learning Models

- Trained models including Logistic Regression, Random Forest, and XGBoost.
- Evaluated performance using metrics like accuracy, precision, recall, and F1-score.

---

## Installation and Requirements

### Libraries

This project requires Python 3.8+ and the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
  -tensorflow

### Installation

To install dependencies:

```bash
pip install -r requirements.txt
```

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/temesgen0/Customer_Churn_Prediction.git
```

2. Navigate to the project directory:

```bash
cd Customer_Churn_Prediction
```

3. Run the notebook:

```bash
jupyter notebook ChurnCustomers.ipynb
```

---

## Project Results

### Model Performance

- Logistic Regression: Accuracy = 75%
- Random Forest: Accuracy = 78%
- XGBoost: Accuracy = 77%
- XGBoost: Accuracy = 75%

### Insights

- Customers with higher monthly charges and shorter tenures are more likely to churn.
- Gender shows minimal impact on churn likelihood.
- Senior citizens have higher churn rates compared to younger customers.

---

## Folder Structure

```
Customer_Churn_Prediction/

├── notebooks/
│   └── ChurnCustomers.ipynb  # Main analysis and modeling notebook
├── models/
│   └── churn_model.pkl  # Saved model
├── requirements.txt  # Python dependencies
├── LICENSE  # Python dependencies
└── README.md  # Project documentation
```

---

## License

This project is licensed under the Apache License.
