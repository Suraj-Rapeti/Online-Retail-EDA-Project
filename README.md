# 📊 Online Retail - Exploratory Data Analysis (EDA) Project

## 📁 Project Overview

This project performs Exploratory Data Analysis (EDA) on a real-world dataset from a UK-based online retail store. The dataset contains transactions from **December 2010 to December 2011**. The main objective is to extract meaningful insights to help improve business decision-making and customer satisfaction.

---

## 📌 Objectives

- Understand sales trends across time.
- Identify best-selling products and most active customers.
- Analyze customer behavior and country-wise sales distribution.
- Detect outliers and anomalies in the dataset.
- Provide actionable, data-driven business recommendations.

---

## 🧰 Tools & Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📂 Dataset

- **Name**: `Online Retail.xlsx`
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail) *(or Coursera-provided data)*
- **Fields**:
  - `InvoiceNo`: Invoice number
  - `StockCode`: Product/item code
  - `Description`: Product description
  - `Quantity`: Units sold
  - `InvoiceDate`: Date and time of purchase
  - `UnitPrice`: Price per item
  - `CustomerID`: Unique customer ID
  - `Country`: Country of purchase

---

## 📊 EDA Tasks Performed

- ✅ Loaded and previewed the dataset
- ✅ Cleaned missing and invalid data (e.g., cancellations, negative values)
- ✅ Created new fields (`TotalPrice`, `Month`, `Hour`, etc.)
- ✅ Analyzed:
  - Monthly and daily sales trends
  - Time-of-day activity
  - Top-selling products
  - Country-wise sales
  - Top customers by revenue
  - Outliers in quantity and unit price
- ✅ Visualized insights using bar charts, histograms, line plots, and boxplots

---

## 📈 Key Insights

- Sales peak during **November and December** (holiday season).
- Most purchases are made during weekdays between **10 AM and 2 PM**.
- UK is the dominant market; **Germany** and **France** are promising for expansion.
- A small set of products contribute to the majority of sales.
- Several outliers were found in pricing and quantity, suggesting data entry issues.

---

## ✅ Business Recommendations

- Increase inventory before the holiday season.
- Focus marketing during peak hours and days.
- Offer loyalty rewards to high-value customers.
- Analyze return-prone products to reduce cancellations.
- Improve data validation at the time of entry.

---

## 🧾 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Suraj-Rapeti/online-retail-eda.git
   cd online-retail-eda
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn openpyxl

