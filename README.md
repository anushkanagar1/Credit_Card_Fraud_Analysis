💳Credit Card Fraud Analysis
📖 Project Overview

This project analyzes a large credit card transaction dataset to identify patterns of fraudulent activity. Using Excel pivot tables and dashboards, the project highlights:

Distribution of fraud vs. normal transactions
Transaction patterns across different time ranges
Relationship between transaction amounts and fraud likelihood
Average fraud transaction amounts compared to normal
The goal of this project is to demonstrate data analysis, visualization, and storytelling skills relevant for business analytics and risk management roles.
<img width="1673" height="636" alt="Screenshot (69)" src="https://github.com/user-attachments/assets/642d4afd-d22f-474a-aafd-8c9744b118c5" />

🗂️ Dataset

Source: Kaggle - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data
Size: ~200MB (not included here due to GitHub file limits)

Columns Used:
Time → converted into Hour and Time Range (Morning, Afternoon, Evening, Late Night)
V1–V28 → anonymized features (not analyzed in Excel version)
Amount → transaction amount in USD
Class → 0 = Normal, 1 = Fraud

🛠️ Methodology

Data Preprocessing
Converted Time into Hour and grouped into time ranges.
Created Amount Bucket categories (<10, 10–100, 100–1000, 1000–5000, >5000).
Cleaned and structured dataset for Excel analysis.

Pivot Tables Created
Fraud vs. Normal Transaction Counts
Fraud by Time Range
Fraud by Amount Bucket
Average Amount by Class

Dashboard in Excel
KPI cards for:
Average Transaction ($)
Total Transactions
Fraud Rate (%)
Average Fraud Amount ($)

Visualizations:
Fraud by Amount Bucket (clustered column chart)
Fraud by Time Range (bar chart)
Fraud vs. Normal (donut chart)
Avg. Amount by Class (bar chart)

📊 Key Insights

Fraud Rate is Very Low: Out of ~285,000 transactions, only 492 were fraud (≈0.17%). This highlights the imbalance problem common in fraud detection.
Fraud by Time Range: Most fraud attempts occurred during the Evening, suggesting a behavioral pattern worth monitoring.

Fraud by Amount:
Majority of fraud cases occurred in transactions between $100–$1000.
Very few frauds were detected in very high-value transactions (> $5000).

Average Transaction Size:
Normal transactions ≈ $88
Fraudulent transactions ≈ $122 → showing frauds tend to involve slightly higher amounts.

Normal transactions ≈ $88

Fraudulent transactions ≈ $122 → showing frauds tend to involve slightly higher amounts.
