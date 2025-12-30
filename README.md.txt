# Regional Sales Analysis using Python

## 📌 Project Overview
This project focuses on analyzing regional transactional sales data to uncover key business insights related to sales performance, profitability, channels, and products.  
The analysis follows a structured data analytics workflow including data understanding, cleaning, feature engineering, and exploratory data analysis (EDA).

---

## 🎯 Objectives
- Understand the structure and quality of transactional sales data
- Clean and prepare data for analysis
- Analyze sales trends over time
- Evaluate channel-wise and product-wise performance
- Identify high-revenue and low-profit products
- Generate actionable business insights from data

---
## 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🗂️ Project Structure
Regional-Sales-Analysis/
│
├── data/
│ ├── raw/ # Original dataset
│ └── processed/ # Cleaned and processed data
│
├── notebooks/
│ ├── 01_data_understanding.ipynb
│ ├── 02_data_cleaning_and_feature_engineering.ipynb
│ └── 03_exploratory_data_analysis.ipynb
│
├── README.md




---

## 📊 Dataset Description
- The dataset contains **transactional sales records**
- Each row represents a valid sales event
- Products are represented using anonymized identifiers (`product_description_index`)
- Repeated order numbers represent valid transactions, not duplicate records

---

## 🧹 Data Cleaning & Feature Engineering
The following steps were performed:
- Converted date columns to datetime format for time-series analysis
- Standardized column names using `snake_case`
- Verified absence of critical missing values
- Retained repeated order numbers after validating transactional integrity
- Created derived metrics:
  - Revenue
  - Total cost
  - Profit
  - Profit margin
- Extracted time-based features such as year and month

---

## 🔍 Exploratory Data Analysis (EDA)

### Key Analyses Performed:
- Overall revenue and profit analysis
- Monthly sales trend analysis
- Channel-wise revenue and profit comparison
- Product-level performance evaluation
- Identification of high-revenue but low-profit products

---

## 📈 Key Insights
- The business operates at a large scale, generating **hundreds of millions in revenue**
- Monthly sales trends are relatively stable with periodic fluctuations
- The **Wholesale channel** is the primary contributor to both revenue and profit
- The **Export channel** contributes the least, indicating potential growth opportunities
- Sales are concentrated among a limited number of products
- Some high-revenue products operate with lower profit margins, suggesting pricing or cost optimization opportunities

---
### Business Recommendations

- Optimize costs for high-revenue, low-margin products through supplier and logistics review.
- Review pricing strategies to improve margins on high-demand products.
- Promote products through higher-margin sales channels.
- Reduce excessive discounting on top-selling products.


---

## 📌 Conclusion
This project demonstrates a complete data analytics workflow from raw data to actionable insights.  
It highlights the importance of understanding data structure, careful data cleaning, and insight-driven analysis to support business decision-making.

---



