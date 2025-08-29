# Credit Card Fraud Detection

This project uses **Machine Learning** to detect fraudulent credit card transactions.  
It is based on the Kaggle Credit Card Fraud dataset, which contains anonymized features of transactions.  

## Project Workflow

1. **Data Preprocessing**  
   - Load dataset  
   - Handle missing values & scaling  
   - Split into training/testing sets  

2. **Exploratory Data Analysis (EDA)**  
   - Fraud vs. Non-Fraud distribution  
   - Correlation heatmap of features  
   - Transaction amount analysis  

3. **Model Training**  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  

4. **Model Evaluation**  
   - Confusion Matrix  
   - Precision, Recall, F1-score  
   - ROC Curve  


## Results

| Model                | Accuracy | Precision (Fraud) | Recall (Fraud) | F1-score (Fraud) |
|-----------------------|----------|-------------------|----------------|------------------|
| Logistic Regression   | 98%      | 0.98              | 0.91           | 0.94             |
| Random Forest         | 99%      | 0.99              | 0.88           | 0.93             |
| XGBoost               | 98%      | 0.98              | 0.91           | 0.94             |




