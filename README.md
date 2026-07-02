<div align="center">

# Apex Project
## Retail & E-Commerce Inventory AI Pipeline

> **BITS Pilani · BS Program · Apex Project · Trimester 3**

![Python](https://img.shields.io/badge/Python-3.10-1a1a1a?style=flat-square&logo=python&logoColor=3776AB)
![Pandas](https://img.shields.io/badge/Pandas-2.2.2-1a1a1a?style=flat-square&logo=pandas&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-1.6.1-1a1a1a?style=flat-square&logo=scikitlearn&logoColor=F7931E)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13.2-1a1a1a?style=flat-square&logoColor=white)
![Colab](https://img.shields.io/badge/Google_Colab-Live-1a1a1a?style=flat-square&logo=googlecolab&logoColor=F9AB00)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1v4uQ6rEmCs6N6Cw4rj3WC9k-OlfJHCnI)

</div>

---

## Student Details

| Field | Details |
|---|---|
| Student | Samarth Rajesh Lad |
| Problem ID | P4 - Retail and E-Commerce: Conversational Inventory AI Pipeline |
| Program | BITS Pilani BS Program, Trimester 3 |
| Instructor | Deepak Bahuguna |

---

## About

Raw retail transaction data is rarely clean. Missing values, wrong 
data types, and inconsistent formatting quietly undermine any 
analysis built on top of them.

This project builds a 14-step end-to-end data cleaning pipeline 
for a retail transactions dataset sourced from Kaggle, transforming 
messy raw data into a clean, structured, analysis-ready dataset.

| | Raw Dataset | Clean Dataset |
|---|---|---|
| **Rows** | 12,575 | 11,362 |
| **Columns** | 11 | 17 |
| **Missing Values** | 7,229 | 0 |
| **Duplicate Rows** | 0 | 0 |

---

## Dataset

**Retail Store Sales - Dirty for Data Cleaning**

Source: [Kaggle](https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning)

**Known issues in raw data:**
- 1,213 missing Item names
- 609 missing Price Per Unit values
- 604 missing Quantity values
- 604 missing Total Spent values
- 4,199 missing Discount Applied values
- Transaction Date stored as plain text
- Quantity stored as float instead of integer
- Discount Applied stored as text instead of boolean

---

## Pipeline Steps

| Step | Activity |
|---|---|
| 1 | Load dataset and inspect structure |
| 2 | Record before snapshot |
| 3 | Remove rows with missing Item names |
| 4 | Check missing Quantity and Total Spent |
| 5 | Fill missing Price Per Unit with category median |
| 6 | Fill missing Discount Applied with False |
| 7 | Convert Transaction Date to datetime format |
| 8 | Convert Quantity from float to integer |
| 9 | Standardize Category and Item text formatting |
| 10 | Label encode categorical columns |
| 11 | Apply MinMaxScaler to numeric columns |
| 12 | Generate before/after data quality report |
| 13 | Produce three analysis charts |
| 14 | Export clean_retail_store_sales.csv |

---

## Key Findings

From the cleaned dataset of 11,362 rows:

- **Butchers** was the top category by total sales (~200,000)
- **Online** and **In-store** channels contributed almost equally
- **Cash** was the most used payment method (~510,000 in sales)

---

## Repository Files

| File | Description |
|---|---|
| `Apex_Project_Samarth_Lad.ipynb` | Main pipeline notebook |
| `Apex_Project_Report_Samarth_Lad.pdf` | Full project report |
| `GenAI_Prompt_Log_Samarth_Lad.pdf` | GenAI usage log |

---

## Tools and Libraries

| Tool | Version | Purpose |
|---|---|---|
| Python | 3.10 | Core programming language |
| Pandas | 2.2.2 | Data loading, cleaning, transformation |
| NumPy | 2.0.2 | Numeric operations |
| scikit-learn | 1.6.1 | LabelEncoder, MinMaxScaler |
| Matplotlib | 3.10.0 | Bar charts and visualizations |
| Seaborn | 0.13.2 | Styled visualizations |
| Google Colab | Latest | Development environment |

---

<div align="center">
  <sub>BITS Pilani BS Program · Apex Project · Trimester 3 · P4</sub>
</div>
