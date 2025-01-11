## Bank Transaction Fraud Detection

### Overview
Fraudulent bank transactions are a significant issue for financial institutions and customers alike. This project aims to efficiently flag potentially fraudulent transactions by using machine learning techniques, including Isolation Forest for anomaly detection and Random Forest for fraud classification, to build a robust fraud detection system. 
The dataset includes bank transaction records with multiple features such as transaction amount, type, time and user information.

### Project Workflow
1. Data Cleaning: 
Handled missing or inconsistent data.
Standardized numerical values for better model performance.
Encoded categorical features where necessary.
3. Exploratory Data Analysis (EDA): 
Explored trends in transaction amounts and types.
Visualized distributions and correlations between features.
Detected patterns and outliers in the transaction data.
4. Data Visualization: 
Plotted trends, outliers, and fraud patterns.
Used heatmaps, histograms, and scatter plots for interpretability.
5. Anomaly Detection with Isolation Forest: 
Trained the Isolation Forest model to detect anomalies in the transaction data.
Flagged anomalous transactions as potential fraud for further analysis.
6. Fraud Classification with Random Forest: 
Built a supervised learning model using Random Forest to classify transactions.
Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.
