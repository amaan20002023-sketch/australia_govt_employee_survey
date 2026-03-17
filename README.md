# 🏛️ DETE Employee Exit Survey — Data Analysis

## 📋 Project Overview

This project analyzes the Employee Exit Survey data from the
**Department of Education, Training & Employment (DETE)**,
Queensland Government, Australia.

The analysis identifies key factors driving employee attrition,
workplace satisfaction levels, and provides data-driven
recommendations to improve retention.

---

## 📁 Repository Structure
```
DETE-Exit-Survey-Analysis/
│
├── 📊 Data/
│   └── Employee_Exit_Survey_Data.xlsx     # Raw dataset (822 records)
│
├── 📈 Analysis/
│   └── DETE_Exit_Survey_Analysis.xlsx     # Cleaned data + EDA + Dashboard
│
├── 📑 Presentation/
│   └── DETE_Exit_Survey_Presentation.pptx # Case study PPT (10 slides)
│
└── README.md
```

---

## 📊 Dataset Information

| Property | Detail |
|---|---|
| **Source** | Queensland Government — DETE |
| **Records** | 822 employees |
| **Columns** | 56 variables |
| **Years** | 2020 – 2024 |
| **Tool Used** | Microsoft Excel + Power Query |

---

## 🔧 Data Cleaning Steps

- Handled missing values (`Not Stated` → Null)
- Converted `TRUE/FALSE` reason columns → `1/0` (Whole Number)
- Standardized date columns (Cease Date, DETE Start Date)
- Calculated **Tenure** = Cease Year − DETE Start Year
- Mapped Likert ratings to numeric scores:
  - `SA=5` `A=4` `N=3` `D=2` `SD=1`
- Fixed data types (ABC 123 → Text / Number / Boolean)
- Loaded to **Data Model** via Connection Only

---

## 📌 Key Findings

1. 🔴 **Work-Life Balance** is #1 exit reason — cited by **26.4%** of employees
2. 📉 **Resignees** have significantly lower satisfaction than retirees
3. 👴 **61+ age group** accounts for the most exits (222 employees)
4. ⚠️ **Opportunities for Promotion** — lowest satisfaction score (**3.35/5**)
5. 👩 **Female employees** = **69.7%** of all exits
6. 🆕 **0–6 year tenure** employees show high early attrition risk

---

## 📈 Satisfaction Analysis

| Dimension | Mean Score | Status |
|---|---|---|
| Peer Support | 4.00 | 🟢 Good |
| Initiative | 3.98 | 🟢 Good |
| Skills | 3.84 | 🟢 Good |
| Stress & Pressure Support | 3.45 | 🟡 Watch |
| Career Aspirations | 3.38 | 🔴 Critical |
| Opportunities for Promotion | 3.35 | 🔴 Critical |
| Wellness Programs | 3.22 | 🔴 Critical |

> Overall Average Satisfaction Score: **3.64 / 5.0**

---

## 💡 Recommendations

| # | Action | Timeline |
|---|---|---|
| 1 | Flexible work arrangements | Short-term |
| 2 | Workload management policy | Short-term |
| 3 | Career development pathways | Medium-term |
| 4 | Leadership & manager training | Medium-term |
| 5 | Staff recognition programs | Medium-term |
| 6 | Early-tenure onboarding program | Short-term |
| 7 | Mental health & EAP expansion | Long-term |
| 8 | Regional salary equity | Long-term |
| 9 | Structured exit interviews | Short-term |
| 10 | Predictive satisfaction tracking | Long-term |

---

## 🛠️ Tools Used

- **Microsoft Excel** — Data cleaning, EDA, Dashboard
- **Power Query (M Code)** — Data transformation & modeling
- **Power Pivot / Data Model** — Relational analysis
- **PivotTables & Charts** — Visual insights

---

## 👤 Author

**Amaan**
Data Analyst
📧 amaan20002023@gmail.com
🔗 https://www.linkedin.com/in/mohammad-amaan-a07494276/
🐙 https://github.com/amaan20002023-sketch

---

## 📄 License

This project is for **educational purposes only**.
Dataset sourced from Queensland Government — DETE.

---

