# Customer Risk, Fraud & Churn Analysis Dashboard (Tableau)

## Objective
To analyze fraud risk, transaction behavior, and customer churn across value-based customer segments, enabling data-driven risk and retention insights.

## Dataset
- Fraud summary (transaction-level fraud indicators)
- Customer segmentation data (Low, Medium, High value)
- Churn rates by customer segment

## Key Metrics
- Overall Fraud Rate (%)
- Fraud vs Non-Fraud Transaction Volume
- Customer Distribution by Segment
- Churn Rate by Customer Segment

## Dashboard Features
- KPI-style Fraud Rate indicator with risk classification
- Log-scale comparison for Fraud vs Non-Fraud transactions
- Interactive filters for Fraud Rate Status and KPI thresholds
- Segment-level churn comparison

## Key Insights
- Fraud rate is extremely low (~0.17%), indicating strong fraud controls.
- Despite low fraud incidence, absolute fraud transaction volume remains non-trivial due to high overall transaction volume.
- Medium and High Value customer segments show significantly higher churn, highlighting retention risk beyond fraud.

## Dashboard Preview
![Customer Risk & Churn Dashboard](credit_analytics/images/dashboard_overview.png)

### Fraud Rate KPI
![Fraud Rate KPI](credit_analytics/images/fraud_rate.png)

## Tools Used
- Tableau Desktop
- CSV data processing
- Calculated fields, KPI indicators, log-scale visualizations

## Outcome
This dashboard enables stakeholders to distinguish between fraud *rate* and fraud *volume*, while identifying churn risk among high-value customers — supporting targeted retention and risk mitigation strategies.
