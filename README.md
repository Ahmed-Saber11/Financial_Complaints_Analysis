## Financial Complaints Analysis & Classification
An end-to-end data science and business intelligence project designed to analyze, visualize, and predict resolutions for consumer financial complaints. 
This repository integrates a machine learning pipeline with a professional Power BI dashboard to transform raw complaint data into actionable insights.

# Overview
Financial institutions receive thousands of complaints daily. This project provides a structured approach to understanding these grievances, identifying geographic and product-based trends, and utilizing Gradient Boosting (XGBoost) to predict company response outcomes with high precision.

# Key Highlights
- Predictive Power: Achieved 96% accuracy in predicting company responses using an XGBoost classification model.
- Interactive BI: Developed a comprehensive Power BI dashboard for real-time monitoring of complaint metrics and regional hotspots.
- Scalable Pipeline: Built a clean, modular Python workflow covering data cleaning, categorical encoding, and performance evaluation.

# Tech Stack
- Analysis & ML: Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Visualizations: Plotly Express, Seaborn, Matplotlib
- Business Intelligence: Power BI Desktop
- Environment:Google Colab

# Project Structure
- Complaints_Analysis.ipynb: Detailed Jupyter Notebook featuring the data preprocessing, exploratory data analysis (EDA), and machine learning training.
- Complaints Analysis.pbix: Interactive Power BI report providing executive-level summaries and drill-down capabilities.
- Consumer_Complaints.xlsx: The source dataset containing over 62,500 records.

# Key Features & Insights
1. Exploratory Data Analysis (EDA)
- Primary Drivers: Identified "Checking or savings accounts" and "Credit cards" as the most frequent sources of friction.
- Geographic Distribution: Heatmaps reveal complaint concentrations across 51 states, led by CA, FL, and NY.
- Timeline Trends: Analyzed complaint volume fluctuations from 2017 to 2023.

2. Machine Learning Workflow
- Data Preparation: Automated handling of missing values and applied LabelEncoder for categorical feature optimization.
- Model Selection: Implemented XGBoostClassifier for its efficiency with structured data and handling of class imbalances.
- Performance Metrics:
    Accuracy: 96%
    Weighted F1-Score: 0.95
    Reliability: High precision across majority classes (e.g., "Closed with explanation").

# Dashboard Preview
The included .pbix file offers:
- Trend Analysis: Year-over-year complaint volume.
- Product Deep-Dive: Breakdown of issues by sub-product and service type.
- Operational Efficiency: Analysis of "Timely Responses" and submission channels (Web, Phone, Referral).

# Conclusion
This project demonstrates the power of combining Machine Learning with Business Intelligence to streamline financial operations. By predicting outcomes and identifying systemic issues, organizations can improve customer satisfaction and regulatory compliance.

 
