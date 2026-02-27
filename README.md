# Chipotle Sales EDA
![Python](https://img.shields.io/badge/Python-3.13-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![EDA](https://img.shields.io/badge/Type-Exploratory%20Data%20Analysis-orange)

📌 End-to-end exploratory data analysis project focused on identifying revenue drivers and understanding customer purchasing behavior.

Exploratory Data Analysis (EDA) of Chipotle sales transaction data using Python, Pandas, and Matplotlib.

## 📓 View Full Analysis
[Open Jupyter Notebook](chipotle_eda.ipynb)

## 📊 Project Overview
This project explores Chipotle sales data to better understand:
- Best-selling menu items by quantity and revenue
- Price distribution and detection of outliers
- Sales patterns across product categories (e.g., Chicken, Steak, Veggie)

The objective of this project is to transform raw transactional data into actionable business insights using structured data analysis and visualization techniques.

## 🛠 Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 📁 Dataset
Chipotle sales dataset in TSV format containing transactional order data.

## 🔍 Key Steps
- Data cleaning and preprocessing (price conversion, missing values handling)
- Feature engineering (unit price, product category extraction)
- Aggregation and exploratory analysis
- Visualization of trends and distributions

## 📈 Key Findings
- Total revenue across all transactions reached approximately **$39,237**.
- The Average Order Value (AOV) was approximately **$21.39 per order**, indicating predominantly individual-sized purchases.
- Revenue shows strong positive correlation with quantity (**r = 0.76**), suggesting sales are primarily volume-driven rather than price-driven.
- Price demonstrates moderate correlation with revenue (**r = 0.61**) but weak correlation with quantity (**r = 0.26**).
- A small number of menu items contribute disproportionately to overall revenue, indicating product concentration.
- Sales performance appears to be demand-driven, with customer purchasing behavior favoring core mid-priced menu items.

## 🚀 Next Steps
- Customer segmentation
- Market basket analysis
- Predictive modeling of sales trends

---

Feel free to explore the notebook to see the full analysis and visualizations.
