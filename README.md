# Superstore Data Analysis 📊

This project explores the **Superstore dataset** using various **data analysis techniques**, including **data cleaning, exploratory data analysis (EDA), visualization, and feature engineering**. The goal is to extract meaningful insights related to **sales, profit, discounts, and customer behavior**.

---

## 📂 Project Overview
The notebook **SuperStore_DataAnalysis.ipynb** performs the following key tasks:

### 🔍 **1. Data Cleaning & Preprocessing**
- Handled encoding issues while loading the dataset.
- Removed missing values and duplicate records.
- Converted **date columns** into a proper datetime format.

### 📊 **2. Exploratory Data Analysis (EDA)**
- **Summary Statistics:** Generated statistical summaries for numerical columns.
- **Boxplots for Outliers:** Visualized data distribution and detected anomalies.
- **Log Transformation:** Applied log scaling to handle highly skewed features.
- **Pairplots:** Examined relationships between key numerical features.

### 🔥 **3. Outlier Detection**
- Identified potential **outliers** using the **Z-score** method.
- Used **IQR-based** detection to highlight extreme values.

### 📈 **4. Visualizations & Business Insights**
- **Sales & Profit Analysis:** Distribution plots and sales trends over months.
- **Category & Regional Performance:** Bar charts showing profits by category and sales by region.
- **Correlation Heatmap:** Analyzed relationships between sales, profit, discount, and quantity.

### 🛠 **5. Feature Engineering**
- Created **log, squared, and cubed transformations** for meaningful insights.
- Calculated **profit margins** and visualized category-wise performance.

---

## 🏗 **Installation & Usage**
### 1️⃣ Clone this repository:
```bash
git clone https://github.com/mkmahsa/SuperStore_DataAnalysis.git
cd SuperStore_DataAnalysis
