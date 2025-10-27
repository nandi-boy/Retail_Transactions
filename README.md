# 🛍️ Retail Transactions Analysis

## 📘 Overview
This project analyzes retail transaction data from a chain operating across multiple cities in India.  
The goal is to **understand customer purchasing behavior**, **seasonal demand**, and **city-level sales performance** to help management make informed decisions about **marketing** and **inventory**.

The project focuses on **data cleaning**, **exploration**, and **visualization** of key business insights.

---

## 🎯 Objectives
- Clean and preprocess messy retail transaction data.
- Identify and handle missing or duplicate values.
- Analyze sales distribution across cities, product categories, and time periods.
- Visualize trends in customer behavior and sales performance.
- Derive actionable insights for strategic decision-making.

---

## 🧩 Dataset
**File:** `Retail_Transactions_2000.csv`  
**Description:** Contains raw transactional data from various retail stores.  

**Columns:**

* `Transaction_ID`   - Unique identifier for each transaction 
* `Customer_ID`      - Unique customer identifier 
* `City`             - Location of the store 
* `Date`             - Transaction date 
* `Product_Category` - Type of product purchased 
* `Quantity`         - Number of units sold 
* `Price`            - Price per unit 
* `Total_Amount`      - Total amount for each transaction 


---

## 🧠 Workflow

### **Step 1 - Import Required Libraries**
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

### **Step 2 - Load the Dataset**
```
data = pd.read_csv("Retail_Transactions_2000.csv")
```

### **Step 3 - Data Cleaning & Preprocessing**
   * Checked for missing values using `isnull().sum()`
   * Removed or imputed null values
   * Checked for duplicates and inconsistent records

### **Step 4 - Exploratory Data Analysis (EDA)**
   * Generated summary statistics using `describe()`
   * Explored sales distribution and trends
   * Visualized product-wise and city-wise sales

### **Step 5 - Visualization**
Visuals were created using Matplotlib and Seaborn:
   * 📊 Bar charts: City-wise sales
   * 🧭 Line plots: Monthly/seasonal trends
   * 🍩 Pie charts: Product category distribution
   * 🔥 Heatmaps: Feature correlations
     
---
📈 Insights (Sample Outcomes)

   * Top-performing cities contribute most to overall sales.
   * Seasonal peaks observed during festive months.
   * Some product categories outperform in specific regions.
   * Customer retention higher in metro cities.
---

## ⚙️ Requirements

* Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn
```

### Python Version: 3.8 or higher
Recommended IDE: Jupyter Notebook / VS Code.

---

## 🧑‍💻 Author
- Ayan Nandi
