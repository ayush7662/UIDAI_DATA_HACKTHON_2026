# Aadhaar Enrolment Data Analysis – UIDAI Hackathon

## 📌 Project Overview
This project analyses Aadhaar Enrolment data released by the Unique Identification Authority of India (UIDAI) to identify meaningful trends, patterns, and insights that can support data-driven decision-making and policy planning.

The analysis focuses on enrolment behaviour over time using feature engineering, exploratory data analysis, and clear visualisation techniques.

---

## 🎯 Problem Statement
To uncover temporal trends and meaningful insights in Aadhaar enrolment data that can help improve enrolment outreach, infrastructure planning, and administrative efficiency.

---

## 📊 Dataset Used
- **Dataset:** Aadhaar Enrolment Data (UIDAI – anonymised public dataset)
- **Format:** CSV
- **Scope:** National-level enrolment records
- **Key Columns Used:**
  - Date
  - Enrolment type fields
  - Total enrolment (engineered column)

State-wise datasets were intentionally excluded to maintain a consistent national-level analysis.

---

## 🛠 Methodology
1. **Data Loading**
   - Combined large CSV files into a single dataframe
2. **Data Cleaning**
   - Handled missing values
   - Converted date columns to datetime format
3. **Feature Engineering**
   - Created a new column `total_enrolment`
4. **Exploratory Data Analysis**
   - Univariate, bivariate, and trivariate analysis
5. **Visualisation**
   - Time-series trends
   - Comparative enrolment patterns
6. **Export**
   - Cleaned dataset saved for reproducibility

---

## 📈 Key Insights
- Aadhaar enrolment shows clear temporal trends with peak periods likely linked to policy drives and awareness campaigns.
- Enrolment activity is not uniformly distributed over time, indicating opportunities for targeted interventions.
- Engineered metrics improve interpretability of enrolment growth patterns.

---

## 🌍 Impact & Applicability
The insights from this analysis can help:
- Government bodies optimise enrolment drives
- Improve infrastructure allocation
- Support data-driven administrative decisions
- Enhance citizen service delivery

---

## 📁 Project Structure
