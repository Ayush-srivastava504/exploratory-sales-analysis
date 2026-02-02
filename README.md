# Exploratory Data Analysis of Sales Dataset (2019)

## 📌 About the Project

This project performs **Exploratory Data Analysis (EDA)** on a real-world **Sales dataset from 2019** using **Python, Pandas, and Matplotlib**.  
The objective is to clean raw sales data, engineer meaningful features, and answer **business-driven questions** through data analysis and visualization.

The notebook follows an **end-to-end data analysis workflow**, making it suitable for **Data Analyst and Junior Data Engineer portfolios**.

---

## 📂 Dataset Description

- The dataset consists of **12 CSV files**, each representing one month of sales data for the year 2019.
- File naming format:  
  `Sales_[MONTH_NAME]_2019.csv`
- Each file contains between **9,000 to 26,000 rows** with the following columns:

| Column Name         | Description |
|---------------------|------------|
| Order ID            | Unique order identifier |
| Product             | Product name |
| Quantity Ordered    | Number of units ordered |
| Price Each          | Price per unit |
| Order Date          | Date and time of order |
| Purchase Address    | Customer purchase address |

---

## 🛠 Tasks Performed

- Merged 12 months of sales data into a single dataset
- Cleaned invalid and missing data
- Engineered new features:
  - **Month** (from Order Date)
  - **Sales** (Quantity × Price)
  - **City** (from Purchase Address)
- Performed aggregation and grouping for insights
- Created visualizations for business interpretation

---

## ❓ Business Questions Answered

1. What was the **best month for sales** and how much revenue was generated?
2. Which **city had the highest sales**?
3. What is the **best time to display advertisements** to maximize purchases?
4. Which **products are most frequently sold together**?
5. Which product sold the **highest quantity**, and why?

---

##  Tools & Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **Matplotlib**
- **OS module**

---

## 📁 Project Structure

exploratory-sales-analysis/
- `dataset/` –  Monthly sales CSV files
- `Sales_Analysis.ipynb /` – Main analysis notebook
- `docs/` – Contains doc and readmes
- `README.md/` – 

## Key Insights

- December recorded the highest sales due to holiday demand
- Peak purchase times were around 11–12 PM and 6–8 PM
- High-priced products sold fewer units but generated significant revenue

##  Author

This project was developed as a **real-world, business-focused analytics case study**, designed to reflect how data is used in **startup and SME environments** for decision-making — moving beyond surface-level dashboards to actionable insights.

<p align="center">
  <b>Ayush Srivastava</b><br>
  Data Analyst | Aspiring Data Engineer<br><br>
  📧 ayushwww4@email.com &nbsp;|&nbsp;
  🔗 <a href="https://www.linkedin.com/in/ayush-srivastava-2b6904262/">LinkedIn</a> &nbsp;|&nbsp;
  🐙 <a href="https://github.com/Ayush-srivastava504">GitHub</a>
</p>

