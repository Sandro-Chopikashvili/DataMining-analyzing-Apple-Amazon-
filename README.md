# 🧠 Advanced Data Mining: Amazon Products & Apple Financials

This repository contains two comprehensive data analysis projects:

1. **Amazon Product Dataset Mining** – Advanced EDA and discount analysis.
2. **Apple Financial Dataset Analysis** – Time-series financial insights using liabilities data.

---

## 📁 Dataset Sources

### 🔹 Amazon Dataset
- Contains product details like actual and discounted prices, ratings, review counts, and discount percentages.
- Cleaned and processed for advanced price and sentiment analysis.

### 🔹 Apple Financial Dataset
- Contains historical financials such as total liabilities over multiple years.
- Used for time-series trend analysis and visualization.

---

## 📊 Amazon Dataset Analysis

### 🛠️ Key Features:
- Price cleaning and conversion using `pandas` string and numeric functions.
- Discount analysis: actual vs discounted prices, % discounts.
- Category-wise aggregation of ratings, discounts, and review volumes.
- Visualizations using `matplotlib` and `seaborn`.

### 📈 Visuals:
- Bar chart of **Top 10 Most Reviewed Products**
- Combo chart of **Average Discount vs. Rating by Category**

### 🧪 Techniques Used:
- Data cleaning (`.str.replace`, `pd.to_numeric`)
- Feature engineering (`discount_amount`)
- Grouping & aggregation (`groupby`, `agg`)
- Dual-axis plots (`matplotlib`, `seaborn`)

---

## 🧾 Apple Financial Dataset Analysis

### 🔍 Focus:
- Visualizing **Total Liabilities** across multiple years to identify growth patterns or financial strategy shifts.

### 🧠 Methods:
- Year-wise grouping and summing of `Liabilities_Total`
- Line plot to show liability trends over time

### 🧰 Tools:
- `pandas` for grouping (`groupby`)
- `matplotlib` for visualization

---

## 🛠️ Technologies Used

- **Python 3.11+**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Code development and exploration

---

## 📂 Structure

```bash
📁 amazon_apple_data_analysis/
├── Amazon_Analysis.ipynb
├── Apple_Analysis.ipynb
├── amazon.csv
├── Apple_DB.csv
└── README.md

