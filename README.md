# Bank Customer Churn Prediction

## Project Overview
This project leverages Machine Learning to identify high-risk banking customers prone to account closure. By analyzing historical transaction data and demographics, this predictive model helps financial institutions proactively address customer dissatisfaction and reduce churn rates.

## Tools & Technologies
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Random Forest, Logistic Regression)
* **Data Visualization:** Matplotlib

## Methodology
1. **Data Preprocessing:** Cleaned and scaled a dataset of 10,000 tabular records, handling categorical variables via One-Hot Encoding.
2. **Model Training:** Split data into training (80%) and testing (20%) sets. Trained multiple classification algorithms to establish a performance baseline.
3. **Evaluation:** The **Random Forest Classifier** emerged as the optimal model, achieving an accuracy of **86.45%**.

## Key Business Insights
Extracted feature importances from the Random Forest model to determine the core drivers of attrition. The analysis revealed:
1. **Complaints are Critical:** Whether a customer had previously filed a complaint was the overwhelming predictor of churn.
2. **Demographic Factors:** Customer age was the second most significant driver, indicating a potential need to tailor banking products for specific age brackets.
3. **Product Engagement:** The number of products a customer held significantly influenced their likelihood to stay with the bank.
