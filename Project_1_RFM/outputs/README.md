# RFM Customer Segmentation Analysis

## Objective
Segment e-commerce customers using Recency, Frequency, and Monetary (RFM) analysis to identify high-value, loyal, and at-risk customers.

## Python Workflow
The complete data cleaning, RFM scoring, and customer segmentation logic was implemented in Python using Pandas.  
The full workflow is available in the Jupyter notebook: `RFM_Project.ipynb`

## Tools
- Python (Pandas, NumPy)
- Tableau Public

## What is RFM?
RFM (Recency, Frequency, Monetary) is a customer segmentation technique used to evaluate customer value based on:
- Recency: how recently a customer made a purchase
- Frequency: how often a customer purchases
- Monetary: how much a customer spends
It is widely used in e-commerce and CRM analytics to prioritize retention, loyalty, and reactivation strategies.

## Segment Definitions
- Champions: Recent, frequent, high-spending customers who contribute the highest revenue
- Loyal Customers: Frequent purchasers with consistent engagement
- Potential Loyalists: Recently active customers with growth potential
- At Risk: Previously valuable customers with declining recent activity
- Lost Customers: Inactive customers with low recency and frequency

## What I Did
- Cleaned transaction-level retail data
- Calculated RFM metrics per customer
- Assigned customer segments based on RFM scores
- Built an interactive Tableau dashboard to visualize insights

## Key Insights
- Champions generate the highest revenue and purchase frequently
- At Risk and Lost Customers show churn signals
- Potential Loyalists are strong retention opportunities

## Tableau Dashboard
https://public.tableau.com/views/RFMSegmentationAnalysisE-commerceCustomers/RFMCustomerSegmentationAnalysis-Dashboard
