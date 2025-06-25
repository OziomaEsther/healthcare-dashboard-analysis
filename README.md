#  Healthcare Data Analysis & Interactive Dashboard

**Mini Project**  
By **Francis Esther**

---

##  Project Overview

This project presents a healthcare data analysis and dashboard report developed using **Excel (Power Query, PivotTables, and PivotCharts)**. The dataset, sourced from **Kaggle**, contains anonymized patient records, including medical conditions, test results, insurance coverage, and billing details.

The primary goal is to extract actionable insights from large scale hospital records and deliver a **dynamic, user-friendly dashboard** to support hospital management, insurance decisions, and clinical policy development.

---

## Dataset Description

- **Source:** Kaggle  
- **Size:** 55,501 records × 15 columns  
- **Key Fields Include:**
  - Patient demographics (age, gender)
  - Admission and discharge info
  - Medical conditions
  - Insurance providers
  - Billing amounts
  - Test outcomes and risk levels

---

## Data Cleaning & Preparation

All data processing was done using **Power Query in Excel**:

- Cleaned/imputed missing values (e.g., discharge date)
- Standardized date formats and categorical fields
- Feature engineering:
  - `Stay Duration`: Calculated from admission and discharge
  - `Age Group`: Created for trend analysis
  - `Billing Category`: Grouped into Low, Medium, High
  - `Risk Factor`: Derived from test results
- Dropped columns: `Hospital` and `Doctor` due to inconsistencies

---

## Dashboard Insights

###  Patient Demographics
- Most patients fall within the **51–60** and **61+** age groups
- Gender distribution is relatively balanced

###  Medical Condition Trends
- Most common conditions: **Arthritis**, **Diabetes**, **Obesity**
- Chronic diseases dominate the **61+** age group

###  Hospital Stay Duration
- **Average stay:** 15.49 days  
- Patients with **Asthma** and **Arthritis** had longer stays

###  Billing & Insurance
- **Average billing per patient:** \$25,610.90  
- **Medicare** covered the highest number of patients  
- **Blue Cross Insurance** had the highest total billing  
- **Elective** and **Emergency** admissions generated the highest costs

### Test Results & Risk Analysis
- **33.51%** of patients had **abnormal test results**  
- High-risk patients were mostly in the **61+** age group

---

## Key Takeaways

- Elderly patients (61+) require more care and cost significantly more
- Chronic illnesses are widespread → preventive care is essential
- Insurance type and admission method strongly affect billing
- Data supports the need for earlier testing and monitoring

---

## Key Recommendations

1. Launch preventive screening programs, especially for the elderly  
2. Identify and prioritize high-risk patients early  
3. Partner with insurance providers for long-term care support  
4. Continue monitoring trends through dashboards  
5. Promote routine diagnostics to enable early intervention

---

## 📂 Files Included

- `Healthcare data assignment.xlsx` – Cleaned dataset
- `Healthcare dataset analysis.xlsx` – Final Excel dashboard with slicers
- `healthcare Data Analysis Report.docx` – Summary documentation
- `README.md` – This file

---

## Author

**Francis Esther**  
GitHub: (https://github.com/OziomaEsther)  
LinkedIn: (www.linkedin.com/in/francis-esther-ozioma-611ba6230)

---

> _“When data meets care, insight leads the way to better health outcomes.”_
