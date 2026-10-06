# Week 2 – Data Collection, Cleaning & Preprocessing

## 📌 Project Overview

This task focuses on the collection, inspection, cleaning, validation, and preprocessing of logistics-related data using Python and Pandas.

The Olist Brazilian E-Commerce Public Dataset was used for the preprocessing work. The customer dataset was analyzed to identify data quality issues and prepare a reliable dataset for further logistics analysis.

## 📊 Dataset

**Dataset:** Olist Brazilian E-Commerce Public Dataset

**File:** `olist_customers_dataset.csv`

### Dataset Characteristics

- Total Records: 99,441
- Total Columns: 5
- Unique Cities: 4,119
- Unique States: 27

### Main Columns

- `customer_id`
- `customer_unique_id`
- `customer_zip_code_prefix`
- `customer_city`
- `customer_state`

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

1. Dataset loading and initial inspection
2. Missing value checking
3. Duplicate record detection
4. Data type correction
5. ZIP-code formatting and validation
6. Text consistency checking
7. Empty value validation
8. Duplicate removal
9. City and state standardization
10. Final data quality verification

## 📋 Data Quality Results

| Check | Result |
|---|---:|
| Total Records | 99,441 |
| Total Columns | 5 |
| Missing Values | 0 |
| Duplicate Records | 0 |
| Invalid ZIP Length | 0 |
| Non-Numeric ZIP Values | 0 |
| Empty City Values | 0 |
| Empty State Values | 0 |

## 📁 Files

- `Olist_Logistics_Data_Preprocessing_Week2.ipynb` – Python preprocessing notebook
- `cleaned_olist_customers.csv` – cleaned dataset
- `Week_2_Report.docx` – detailed task report

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- VS Code

## ✅ Outcome

The dataset was successfully cleaned, validated, and exported as `cleaned_olist_customers.csv`. The preprocessing provides a consistent dataset that can be used for further logistics analysis.

## 👩‍💻 Author

**Palak Bhargav**
