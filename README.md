🛍️ Retail Sales EDA & Business Insights
📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of retail sales data to uncover actionable business insights. The analysis helps identify sales trends, customer purchasing behavior, profit margins, and product performance.

The goal is to showcase data cleaning, feature engineering, and visualization skills using Python, SQL, Excel, and Power BI — tools essential for a data analyst role.

🗂️ Repository Structure
retail-sales-eda/
│
├── data/                 # Sample dataset (only small files, original source linked in README)
├── notebooks/            # Jupyter Notebooks with step-by-step EDA
├── sql_queries/          # SQL scripts for analysis
├── excel_analysis/       # Pivot tables, charts & Excel-based insights
├── dashboard/            # Power BI dashboard files + screenshots
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

⚙️ Tech Stack

Python → pandas, numpy, matplotlib, seaborn

SQL → Business queries for KPIs (joins, aggregations, window functions)

Excel → Pivot tables, sales dashboards, basic analysis

Power BI → Interactive visual dashboards for decision-making

📊 Business Questions Answered

✔️ Which month records the highest and lowest sales?
✔️ Which regions contribute the most revenue?
✔️ Who are the top customers by sales volume?
✔️ Which product categories drive profitability?
✔️ What is the trend of sales vs. profit margins?
✔️ How does discounting impact profitability?

🔎 Methodology
Step 1: Data Loading & Exploration

Loaded raw sales data (CSV format)

Checked missing values, duplicates, and data consistency

Step 2: Data Cleaning

Handled missing entries

Removed duplicates

Converted dates into Order Month, Order Year for trend analysis

Step 3: Feature Engineering

Created Profit Margin = Profit / Sales

Extracted Month & Year from date field

Categorized sales into high / medium / low performing segments

Step 4: Exploratory Data Analysis (EDA)

Trend analysis by month & year

Region-wise revenue comparison

Customer segmentation

Category-wise profitability

Step 5: Visualization

Matplotlib & Seaborn for heatmaps, bar charts, line plots

Excel pivot charts for business reporting

Power BI dashboard for interactive storytelling

📈 Key Insights

🔹 Sales peak in December due to holiday demand.
🔹 Technology category contributes maximum revenue, but Office Supplies has higher profit margins.
🔹 West region is the strongest market, while South underperforms.
🔹 A small percentage of top customers contribute disproportionately to overall sales (Pareto principle).
🔹 High discounts increase sales volume but significantly reduce profit margins.

📊 Dashboard Preview

📌 Power BI Dashboard Example:

(For full interactive dashboard, download from /dashboard folder)

🗄️ Dataset

Source: Kaggle Retail Dataset (or specify your actual source)

Rows: ~10,000 transactions

Columns: Customer, Product, Category, Region, Sales, Quantity, Profit, Discount, Date

🚀 How to Run Locally

Clone repo

git clone https://github.com/yourusername/retail-sales-eda.git
cd retail-sales-eda


Install dependencies

pip install -r requirements.txt


Open Jupyter Notebook

jupyter notebook notebooks/retail_sales_eda.ipynb
