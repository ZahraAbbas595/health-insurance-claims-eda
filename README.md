🏥 Health Insurance Claims Analysis (EDA Project)
📌 Project Overview

This project presents an end-to-end exploratory data analysis (EDA) of a health insurance claims dataset. The goal is to demonstrate a structured analytical workflow — from data understanding and validation to exploratory analysis, interpretation, and documentation — using a controlled, high-quality dataset.

The project emphasizes analytical discipline, transparent reasoning, and professional reporting rather than aggressive data cleaning or predictive modeling.

🎯 Objectives

Understand the structure and characteristics of health insurance claims data

Perform a comprehensive data quality audit

Explore claim cost behavior, demographics, claim types, and temporal trends

Interpret findings from a business and insurance analytics perspective

Clearly communicate limitations of synthetic and balanced data

📂 Dataset Description

Source: Kaggle (synthetic health insurance claims dataset)  https://www.kaggle.com/datasets/leandrenash/enhanced-health-insurance-claims-dataset?utm_source=chatgpt.com 

Type: Public, educational dataset

Nature: Clean, structured, and balanced

Unit of Analysis: One row per insurance claim

Key Features

Claim amount and claim status

Patient demographics (age, gender, income, employment status)

Provider characteristics (specialty, location)

Claim type and submission method

Claim date for time-based analysis

⚠️ Note: This dataset is synthetically generated and does not reflect real-world noise, bias, or extreme cost skew commonly found in production insurance data.

⬇️ How to Download the Dataset

Visit the dataset page on Kaggle
👉 https://www.kaggle.com/datasets/leandrenash/enhanced-health-insurance-claims-dataset?utm_source=chatgpt.com

Click Download (Kaggle account required)

Extract the dataset and place the CSV file in your working directory

Update the file path in the notebook if necessary:

df = pd.read_csv("health_insurance_claims.csv")

🛠️ Methodology

The analysis followed a structured workflow:

Project Framing & Data Understanding

Defined business context and analytical goals

Reviewed dataset structure and variable types

Data Quality Audit

Checked for missing values, duplicates, and invalid entries

Validated data types and logical consistency

Confirmed high initial data quality

Data Preprocessing

Minimal corrective cleaning due to clean dataset

Standardized categorical formatting

Feature engineering for segmentation and time analysis

Exploratory Data Analysis (EDA)

Univariate analysis of numerical and categorical variables

Bivariate and multivariate analysis across demographics and claim types

Time-based analysis of claim volume and average cost

Interpretation & Reporting

Business-focused interpretation of neutral findings

Honest discussion of dataset limitations

📊 Key Findings

Claim amounts are evenly distributed with no extreme cost concentration

No strong relationship exists between claim cost and patient demographics

Claim types exhibit similar cost distributions

Claim volume and average cost remain stable over time

Claim outcomes are evenly balanced across approval statuses

Overall, the dataset reflects a controlled and standardized claims environment.

🧠 Business Interpretation

From an insurance analytics perspective, the observed patterns suggest:

Standardized pricing or capped reimbursement structures

Balanced claim processing behavior

Limited financial risk concentration

Stable operational demand over time

While realistic in structure, the dataset does not support advanced risk stratification or predictive modeling due to limited signal.

⚠️ Limitations

The dataset is synthetic and highly balanced

Real-world insurance data typically contains skew, noise, and missingness

Weak feature–target relationships limit statistical inference

Not suitable for fraud detection or production-grade modeling

These limitations are acknowledged and discussed transparently.

🚀 Future Work

Apply the same analytical framework to a more complex, real-world dataset

Perform pricing and risk analysis using datasets with stronger cost drivers

Extend analysis to predictive modeling where appropriate

Compare synthetic vs real-world insurance data behavior

📦 Repository Contents

insurance_claims_eda.ipynb – Main analysis notebook

README.md – Project overview and documentation

data/ – Dataset files (if included)

✅ Portfolio Notes

This project is intended as a practice and methodology demonstration, showcasing:

Clean analytical structure

Professional documentation

Honest interpretation of results

Readiness for more complex analytics projects

👤 Author

Zahra Abbas
Data Science Undergraduate | Aspiring Data Analyst
