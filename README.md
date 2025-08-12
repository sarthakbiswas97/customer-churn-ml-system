
Problem Statement
The objective of this project is to build a binary classification model that predicts the probability a telecom customer will churn in the next billing period. The target variable, Churn, indicates whether a customer has discontinued service (Yes) or remained (No). By accurately identifying likely churners, the business can proactively engage them with retention offers, reducing unnecessary outreach costs while still capturing the majority of true churners. This balance is critical for maximizing retention ROI and improving long-term customer value.

Scope
This project aims to predict customer churn for a telecom provider using the IBM Telco Customer Churn dataset. The goal is to build a binary classification model that helps reduce churn-related costs while maintaining high recall for identifying actual churners.

Dataset
Source: IBM Sample Data Sets – Telco Customer Churn (link)
Target variable: Churn (Yes/No)
Exclusions: customerID
Special handling: Coerce TotalCharges from string to numeric where needed.

Planned Stack

Data processing & modeling: Python, Pandas, NumPy, scikit-learn

EDA & visualization: Matplotlib, Seaborn

Deployment: Flask/FastAPI backend, Next.js frontend, Docker, Kubernetes