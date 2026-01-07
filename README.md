******🛒 E-commerce Sales Performance Dashboard (2023–2024)******

End-to-End Data Analytics Project | Python + Tableau
Author: Mohammad Zaid

1️⃣ Project Overview

This project analyzes 200,000+ e-commerce orders across 2023–2024 to evaluate sales performance, payment behavior, returns, and regional trends.

The objective is to generate actionable business insights that help stakeholders:

Track revenue health

Identify operational risks (returns, COD)

Optimize regional and payment strategies

The workflow reflects how Business Intelligence / Analytics teams operate in real companies.

2️⃣ Business Questions

How is revenue trending month-over-month across 2023–24?

Which payment methods contribute most to returns?

Which states drive the highest revenue and orders?

How do returns impact net revenue?

Which KPIs best represent overall business performance?

3️⃣ Dataset

Records: 200,000+ orders

Level: Order-level transactional data

Time Period: 2023–2024

⚠️ Due to GitHub’s 25MB limit, the dataset is shared as a ZIP file.

🔗 Dataset (ZIP):
https://github.com/zaidm4562-prog/Large-ecommerce-dataset-analysis/blob/main/large_ecommerce_dataset.zip

4️⃣ Tools & Technologies

Python — data cleaning & feature engineering

Pandas — transformations & aggregations

Tableau Public — interactive dashboards

Google Colab — analysis environment

5️⃣ Data Cleaning & Transformation (Python)

Performed in Google Colab.

Steps:

Handled missing values

Removed duplicate records

Standardized data types

Feature Engineering:

Order Month

Order Weekday

Delivery Time

Net Revenue

Return Flag (Is Returned)

COD Indicator

📓 All transformations are documented in:
Notebook.ipynb

6️⃣ Key Performance Indicators (KPIs)

KPI	Value
Total Revenue	$146,176,385
Total Orders	39,795
Average Order Value (AOV)	$3,673
Return Rate	7.17%
COD Order Share	45.05%
Metric Definitions

Return Rate = Returned Orders / Total Orders

COD Share = COD Orders / Total Orders

Net Revenue excludes returned orders

7️⃣ Dashboard Overview

🔗 Live Tableau Dashboard
https://public.tableau.com/views/E-commerceSalesPerformanceDashboard202324/Dashboard1

Dashboard Sections:

KPI Summary Cards — Revenue, Orders, AOV, Returns, COD Share

Payment Method Analysis — COD vs Digital payments

Monthly Revenue Trends — Seasonal patterns

State-wise Sales Performance — Top & low performing states

Return Analysis — Impact of returns on revenue

8️⃣ Key Insights

Nearly 45% of orders are COD, which shows a higher return probability.

Returns significantly reduce net revenue, especially in specific states.

Revenue exhibits clear seasonal fluctuations, useful for campaign planning.

A small set of states contributes a disproportionate share of total revenue.

9️⃣ Business Recommendations

Reduce COD Dependency
Promote prepaid orders via incentives and faster delivery.

Control Returns in High-Risk Regions
Investigate logistics and product quality issues in high-return states.

Seasonal Demand Planning
Align inventory and promotions with revenue cycles.

Track Net Revenue, Not Just Gross Sales
Returns materially impact profitability and should be monitored closely.

🔟 Project Structure
Large-ecommerce-dataset-analysis/
│
├── Notebook.ipynb              # Data cleaning & analysis
├── data/
│   └── large_ecommerce_dataset.zip
├── tableau/
│   └── dashboard.png
├── README.md



This project demonstrates:

Handling of large-scale datasets

Strong Python-based data preparation

KPI-driven business analysis

Professional Tableau dashboarding

Ability to translate data into business decisions

🔚 Note

This project focuses on descriptive and diagnostic analytics, complementing advanced SQL / cohort / LTV projects in the portfolio.
