# Credit Card Fraud Detection

## Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Utilizing the Kaggle credit card fraud dataset, the goal is to build an accurate and reliable model that identifies fraudulent activities with high precision and recall.

## Dataset
The dataset is sourced from Kaggle: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- Contains transactions made by European cardholders in September 2013.  
- Highly imbalanced: Fraudulent transactions account for a very small fraction of the total.

## Methodology
- **Data Preprocessing:** Checked for missing values, scaled features where necessary.  
- **Exploratory Data Analysis (EDA):** Visualized class distribution, transaction amounts, and correlations.  
- **Modeling:**  
  - Used XGBoost classifier for fraud detection.  
  - Performed hyperparameter tuning with GridSearchCV to optimize model performance.  
  - Evaluated model using precision, recall, f1-score, confusion matrix, and ROC-AUC.

## Results
- Best model parameters: `learning_rate=0.1, max_depth=7, n_estimators=200, subsample=0.7`  
- Achieved a ROC-AUC score of approximately 0.98  
- Precision and recall for the fraud class are high, ensuring both accuracy and sensitivity.

## Usage
1. Clone the repository:  
   ```bash
   git clone https://github.com/erdembrn34/credit-card-fraud.git


