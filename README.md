# Logistics Data Analytics Project

## 📌 Project Overview

This project focuses on applying Python-based data analytics techniques to logistics and supply chain data. The project is being developed progressively through multiple tasks, covering data preprocessing, exploratory data analysis, visualization, predictive modeling, and optimization.

The project uses the Olist Brazilian E-Commerce Public Dataset as the primary data source for the initial analysis and preprocessing work.

---

## 🎯 Project Objectives

- Collect and prepare logistics-related data
- Clean and preprocess raw datasets
- Identify and resolve data quality issues
- Perform exploratory data analysis (EDA)
- Create meaningful visualizations
- Identify patterns and insights from logistics data
- Develop predictive models for logistics-related metrics
- Propose data-driven optimization strategies

---

## 📊 Dataset

**Dataset:** Olist Brazilian E-Commerce Public Dataset

For the preprocessing task, the customer dataset contains:

- **99,441 records**
- **5 columns**
- **4,119 unique cities**
- **27 states**

### Main Columns

- `customer_id`
- `customer_unique_id`
- `customer_zip_code_prefix`
- `customer_city`
- `customer_state`

---

# 📁 Week 2 – Data Collection, Cleaning & Preprocessing

### Objective

The Week 2 task focuses on preparing logistics-related data for further analysis by performing data inspection, cleaning, validation, and preprocessing using Python and Pandas.

### Preprocessing Performed

- Dataset loading and inspection
- Missing value checking
- Duplicate record detection
- Data type correction
- ZIP-code validation
- Text standardization
- Empty value validation
- Final data quality verification
- Cleaned dataset export

### Data Quality Results

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

### Output

The cleaned dataset was saved as:

`cleaned_olist_customers.csv`

---

# 📈 Week 3 – Exploratory Data Analysis & Visualization

### Objective

The Week 3 task focuses on exploring the logistics dataset through statistical analysis and visualizations to identify patterns, distributions, trends, and useful operational insights.

### Analysis Performed

- Exploratory Data Analysis
- Customer distribution by state
- Top states by customer count
- Top cities by customer count
- Customer percentage analysis
- Regional analysis
- Data visualization using Python
- Interpretation of analytical findings

### Visualizations

The analysis includes charts representing:

- Customer distribution by state
- Top 10 cities by customer count
- Customer percentage by state

The visualizations help identify geographical customer concentration and support data-driven interpretation of logistics patterns.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- VS Code
- GitHub

---

## 📂 Project Structure


Logistics_Data_Analytics_Project/
│
├── Week_2_Data_Preprocessing/
│   ├── Olist_Logistics_Data_Preprocessing_Week2.ipynb
│   ├── cleaned_olist_customers.csv
│   └── Week_2_Report.docx
│
├── Week_3_EDA_Visualization/
│   ├── Olist_Logistics_EDA_Week3.ipynb
│   └── Week_3_Report.docx
│
├── olist_customers_dataset.csv
└── README.md
---
Future Work

The project will be further extended with predictive modeling and optimization techniques for logistics systems, including model development, performance evaluation, and data-driven optimization recommendations.

👩‍💻 Author

Palak Bhargav

B.Tech Computer Science with AI
