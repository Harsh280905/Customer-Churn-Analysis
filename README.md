# Customer-Churn-Analysis
End-to-end machine learning system to predict customer churn and generate business decisions.


## Project Overview
Customer churn is a major challenge for telecom companies, as retaining existing customers is significantly more cost-effective than acquiring new ones.  
This project implements an **end-to-end machine learning system** that predicts customer churn and converts predictions into **actionable business insights**.

The system enriches raw customer data with churn risk, financial impact, customer lifetime value (CLV), and retention strategy recommendations.

---

## Problem Statement
Telecom businesses need answers to the following questions:
1. Which customers are likely to churn?
2. What is the financial impact if they leave?
3. Which customers should be prioritized for retention?
4. What action should be taken for each customer?

This project addresses all four questions in a single pipeline.

---

## Solution Approach
The project is designed using a **decision-oriented ML architecture**, clearly separating:
- **Model logic** (churn prediction)
- **Business logic** (financial impact, segmentation, CLV)

This structure mirrors real-world production ML systems used in industry.

---

## Model
A **Random Forest Classifier** is used for churn prediction due to its ability to:
- Capture non-linear relationships
- Handle mixed feature types effectively
- Provide feature importance for interpretability
- Perform robustly on real-world tabular data

The model outputs churn probability, which drives all downstream business decisions.

---

## Key Features
- Churn probability prediction for each customer
- Risk categorization (Low / Medium / High)
- Expected annual revenue loss estimation
- Customer Lifetime Value (CLV) calculation
- Risk × Value based retention strategy recommendation
- Batch processing support for CSV / Excel / DataFrame inputs

---

## Workflow
1. Data preprocessing and feature alignment
2. Churn probability prediction using machine learning
3. Financial impact calculation using usage charges
4. Customer segmentation based on churn risk and value
5. CLV estimation for long-term planning
6. Generation of a final enriched customer table

---

## Output
The final output is a **business-ready customer table** containing:
- Churn Probability
- Churn Risk Category
- Expected Annual Financial Impact
- Recommended Retention Action
- Customer Lifetime Value (CLV)

This output can be directly used by retention teams, marketing campaigns, CRM systems, and business dashboards.

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

## Why This Project Matters
This project goes beyond model accuracy and demonstrates how machine learning can be transformed into a **decision support system**.  
It showcases skills in ML pipeline design, business reasoning, and scalable data processing.

---

## Future Improvements
- Deploy as a web application using Streamlit or Flask
- Add model explainability using SHAP
- Integrate real-time prediction APIs
- Improve CLV estimation using survival analysis

---

## Author
Harsh Patil  
Computer Engineering Student | Machine Learning Enthusiast
