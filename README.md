# Health Insurance Claims Analysis (EDA Project)

## Project Overview

This project presents an end-to-end exploratory data analysis (EDA) of a health insurance claims dataset. The objective is to demonstrate a structured and disciplined analytical workflow — from data understanding and validation to exploratory analysis, interpretation, and documentation — using a controlled, high-quality dataset.

The focus of this project is on analytical reasoning, transparency, and professional reporting rather than extensive data cleaning or predictive modeling.

---

## Objectives

- Understand the structure and characteristics of health insurance claims data  
- Perform a comprehensive data quality assessment  
- Explore claim cost behavior, demographics, claim types, and temporal trends  
- Interpret findings from a business and insurance analytics perspective  
- Clearly communicate the limitations of synthetic and balanced data  

---

## Dataset Description

- **Source:** Kaggle (Synthetic Health Insurance Claims Dataset)  
  https://www.kaggle.com/datasets/leandrenash/enhanced-health-insurance-claims-dataset

- **Type:** Public, educational dataset  
- **Nature:** Clean, structured, and balanced  
- **Unit of Analysis:** One row represents one insurance claim  

### Key Features

- Claim amount and claim status  
- Patient demographics (age, gender, income, employment status)  
- Provider characteristics (specialty, location)  
- Claim type and submission method  
- Claim date for time-based analysis  

**Note:** This dataset is synthetically generated and does not reflect real-world noise, bias, or extreme cost skew commonly observed in production insurance data.

---

## How to Download the Dataset

1. Visit the dataset page on Kaggle:  
   https://www.kaggle.com/datasets/leandrenash/enhanced-health-insurance-claims-dataset

2. Click **Download** (Kaggle account required)

3. Extract the dataset and place the CSV file in your working directory

4. Update the file path in the notebook if required:

df = pd.read_csv("health_insurance_claims.csv")
--

## Methodology
The analysis follows a structured and transparent workflow:

1. **Project Framing and Data Understanding**
- Defined analytical objectives and business context

- Reviewed dataset structure and variable types

2. **Data Quality Audit**
- Checked for missing values, duplicates, and invalid entries

- Validated data types and logical consistency

- Confirmed high initial data quality

3. **Data Preprocessing**
- Minimal corrective cleaning due to dataset completeness

- Standardized categorical variables

- Feature engineering for segmentation and time-based analysis

4. **Exploratory Data Analysis**
- Univariate analysis of numerical and categorical variables

- Bivariate and multivariate analysis across demographics and claim types

- Time-based analysis of claim volume and average cost

5. **Interpretation and Reporting**
- Business-oriented interpretation of findings

- Transparent discussion of dataset limitations

## Key Findings
- Claim amounts are evenly distributed with no extreme cost concentration

- No strong relationship is observed between claim cost and patient demographics

- Claim types exhibit similar cost distributions

- Claim volume and average cost remain stable over time

 - Claim outcomes are evenly balanced across approval statuses

- Overall, the dataset reflects a controlled and standardized claims environment.

## Business Interpretation
- From an insurance analytics perspective, these patterns suggest:

- Standardized pricing or capped reimbursement structures

- Balanced and consistent claim processing behavior

- Limited financial risk concentration

- Stable operational demand over time

- While structurally realistic, the dataset does not provide strong signals for advanced risk stratification or predictive modeling.

## Limitations
- The dataset is synthetic and highly balanced

- Real-world insurance data typically exhibits skew, noise, and missing values

- Weak feature–target relationships limit statistical inference

- Not suitable for fraud detection or production-grade modeling

- These limitations are acknowledged and discussed throughout the analysis.

## Future Work
- Apply the same analytical framework to real-world insurance datasets

- Perform pricing and risk analysis using datasets with stronger cost drivers

- Extend the analysis to predictive modeling where appropriate

- Compare synthetic and real-world insurance data behavior

## Repository Contents
- insurance_claims_eda.ipynb — Main analysis notebook

- README.md — Project overview and documentation

- data/ — Dataset files (if included)

## Portfolio Notes
- This project is intended as a demonstration of analytical methodology and reporting quality, highlighting:

- Clean and structured analysis

- Professional documentation

- Honest and transparent interpretation of results

- Readiness for more complex data analytics projects

## Author
Zahra Abbas
Data Science Undergraduate
Aspiring Data Analyst
