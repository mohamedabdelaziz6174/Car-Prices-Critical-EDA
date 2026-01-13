# Under the Hood: A Critical EDA of Car Prices 🚗🔍

## 📌 Project Overview
Not all data is created equal. This project is a **Critical Exploratory Data Analysis (EDA)** of a dataset containing 2,500 car transactions. 

While the initial goal was to analyze market trends and price drivers, the investigation took a turn towards **Data Auditing**. The project serves as a case study in distinguishing between "clean data" (technically correct) and "real data" (logically correct).

## 📂 The Dataset
* **Subject:** Used Car Sales.
* **Records:** 2,500 entries.
* **Format:** CSV (Clean format, no missing values).

## 🕵️‍♂️ The Investigation (Methodology)
Instead of rushing to build a predictive model, I performed a deep dive into the data logic:
1.  **Univariate Analysis:** Analyzing distributions of prices and years.
2.  **Bivariate Analysis:** Checking correlations (e.g., Year vs. Price).
3.  **Logical Validation:** Cross-referencing features with real-world automotive knowledge.

## 🚨 Key Findings (The "Smoking Gun")
Despite having 0 null values and perfect data types, the dataset revealed critical logical flaws proving it is **Synthetic/Fake**:
* **Gas-Powered Teslas:** The dataset lists Tesla models with "Gasoline" engines, which is physically impossible.
* **No Depreciation:** The economic laws of depreciation do not apply; older cars do not correlate with lower prices.
* **Random Pricing:** Prices appeared independent of features like mileage or condition.

## 💡 Conclusion & Takeaway
**"Clean data is not always Real data."**
This project highlights the importance of **Domain Knowledge** in Data Science. A predictive model built on this dataset would be useless in the real world. 
* **Verdict:** This dataset is a sandbox for coding practice, but unfit for market analysis.

## 🧰 Tech Stack
* **Python**
* **Pandas** (Data Manipulation)
* **Matplotlib & Seaborn** (Visual Forensics)

---
*Created by: Mohamed AbdelAziz*
