# 📊 Instagram Analytics Dashboard (Power BI Project)

## 🚀 Project Overview

This project focuses on analyzing Instagram post performance using a structured data pipeline and interactive Power BI dashboard.

The workflow includes:

* Data preprocessing using Python (pandas)
* Data transformation using Power Query
* Visualization and KPI analysis using Power BI

---

## 🧾 Dataset

The dataset contains Instagram post-level data with features such as:

* Post ID
* Upload Date
* Media Type
* Likes, Comments, Shares, Saves
* Reach & Impressions
* Hashtags Count
* Followers Gained
* Traffic Source
* Engagement Rate
* Content Category

---

## 🔧 Data Processing Workflow

### 🔹 1. Data Cleaning (Python - Google Colab)

The dataset was initially processed using pandas to handle:

* Missing values
* Duplicate records
* Inconsistent categorical values
* Invalid entries in numeric columns
* Outliers and formatting issues

---

### 🔹 2. Data Transformation (Power Query)

Further cleaning and transformation were performed in Power BI using Power Query:

* Data type corrections
* Text standardization (trimming, casing)
* Removal of errors
* Final data validation

---

## 📊 Dashboard Overview

The final dashboard provides a comprehensive view of Instagram performance:

### 🔹 Key KPIs

* Revenue (Likes)
* Cost (Comments)
* Profit
* Profit Margin
* Total Reach

---

### 🔹 Visualizations

* 📈 Revenue vs Profit Trend (Line Chart)
* 📊 Revenue by Category (Bar Chart)
* 🥧 Revenue by Traffic Source (Pie Chart)
* 📊 Profit by Media Type (Column Chart)
* 📊 Engagement Rate by Category

---

### 🔹 Filters / Slicers

* Upload Date
* Content Category
* Media Type
* Traffic Source

---

## 💡 Key Insights

* Identifies high-performing content categories
* Compares performance across media types
* Tracks engagement trends over time
* Analyzes traffic source contribution

---

## 🛠️ Tools & Technologies

* Python (pandas, NumPy)
* Google Colab
* Power BI (Power Query + DAX)

---

## 📌 Project Workflow Summary

1. Raw data preprocessing using pandas
2. Data refinement using Power Query
3. KPI creation using DAX
4. Dashboard development in Power BI

---

## 📷 Dashboard Preview

![Dashboard Screenshot](dashboard.png)

---

## 📁 Repository Structure

```
├── data/
│   ├── raw_dataset.csv
│   ├── cleaned_dataset.csv
├── notebooks/
│   └── data_cleaning.ipynb
├── powerbi/
│   └── Instagram_Analytics.pbix
├── images/
│   └── dashboard.png
└── README.md
```

---

## ✨ Conclusion

This project demonstrates an end-to-end data analytics workflow, transforming raw social media data into actionable insights using modern data tools.

---
