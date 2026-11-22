Bank Marketing Campaign Analysis – Exploratory Data Analysis (EDA)

Project Overview:
This project focuses on Exploratory Data Analysis (EDA) of a Bank Marketing Dataset to understand customer behaviour and identify patterns associated with term deposit subscriptions.

The analysis explores customer demographics, financial information, loan status, campaign interactions and previous marketing outcomes using Python.

Project Objectives:
- Understand customer characteristics and behaviour.
- Analyze factors associated with term deposit subscriptions.
- Explore the relationship between campaign contacts and customer responses.
- Identify patterns in previous marketing campaign outcomes.
- Generate meaningful insights through data visualization.

Project Structure:

bank-marketing-eda/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── README.md
│
├── reports/
│   ├── README.md
│   └── key_findings.md
│
├── presentation/
│   └── README.md
│
├── README.md
└── requirements.txt

Exploratory Data Analysis

The following analyses were performed:
1. Data loading and inspection
2. Target variable distribution
3. Customer age group analysis
4. Job and education analysis
5. Marital status analysis
6. Account balance distribution
7. Housing loan and personal loan analysis
8. Campaign contact frequency analysis
9. Previous campaign outcome analysis
10. Call duration analysis
11. Correlation analysis using a heatmap

Key Findings:
1. Housing Loan
- Customers without housing loans showed a subscription rate of approximately 16.70%.
- Customers with housing loans showed a subscription rate of approximately 7.70%.

2. Personal Loan
- Customers without personal loans had a subscription rate of approximately 12.66%.
- Customers with personal loans had a subscription rate of approximately 6.68%.

3. Campaign Contacts
- Most customers were contacted between 1 and 3 times.
- Subscription rates generally decreased with increasing contact frequency.

4. Previous Campaign Outcome
- Customers with a successful previous campaign outcome showed the highest subscription rate.
- The subscription rate was approximately 64.73% for this group.

5. Call Duration
- Average duration for non-subscribers: 221.18 seconds.
- Average duration for subscribers: 537.29 seconds.

6. Correlation Analysis
- "pdays" and "previous" showed a positive correlation of approximately 0.45.
- Most numerical variables showed weak linear correlations.

Business Recommendations:
- Focus on customers who have responded positively to previous campaigns.
- Analyze customer loan status when planning marketing strategies.
- Avoid excessive repeated contact with the same customers.
- Study successful customer interactions to improve campaign engagement.
- Use data-driven customer segmentation for better targeting.

Conclusion:

This project demonstrates how Exploratory Data Analysis can help understand customer behaviour and marketing campaign performance.
The analysis identified useful patterns related to customer financial status, previous campaign outcomes, contact frequency and call duration.
These insights can support better marketing decisions and help improve future campaign strategies.

Future Scope:
- Build a machine learning model to predict customer subscriptions.
- Perform customer segmentation.
- Compare different classification algorithms.
- Improve campaign targeting using predictive analytics.

Author:
Siddhartha Kumar

Project: Bank Marketing Campaign Analysis using Python.
