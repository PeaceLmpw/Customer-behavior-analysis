# Customer-behavior-analysis
A data-driven project that starts from an Excel-based overview and progresses through Python-based cleaning, SQL analysis, and Power BI dashboards to derive actionable business insights.

Customer Shopping Analytics
A data-driven project that starts from an Excel-based overview and progresses through Python-based cleaning, SQL analysis, and Power BI dashboards to derive actionable business insights.

What this project covers

Dataset overview and lineage: from raw Excel-style exploration to clean, analysis-ready data.

Data cleaning in Python: handling missing values, standardizing column names, and feature engineering.

SQL analytics: measuring key business metrics and performing customer segmentation and product performance analysis.

Visualization: interactive dashboards built in Power BI to tell the data story.

Project flow

Excel/journal overview

Initial dataset inspection and understanding of columns, data types, and potential quality issues.

Python data cleaning

Load dataset into a DataFrame.

Inspect structure with information and summary statistics.

Handle missing values (e.g., imputation where appropriate).

Normalize and rename columns for readability (snake_case).

Feature engineering:

Age groups from Age.

Purchase frequency metrics from purchase history.

Data quality checks and redundancy removal (e.g., ensure only necessary fields remain).

Load cleaned data into PostgreSQL for downstream SQL analysis.

SQL analysis (Business Transactions)

Revenue analysis by gender.

Discount behavior and its effect on spending.

Top products by rating and by category.

Shipping type impact on purchase value.

Subscribers vs non-subscribers revenue comparison.

Discount-driven product insights.

Customer segmentation (New, Returning, Loyal).

Repeat buyers and subscription propensity.

Revenue by age group.

Power BI dashboard

Interactive visuals and filters to explore the above analyses.

Clear storytelling with different perspectives (demographics, product performance, and purchasing behavior).

Business recommendations

Boost subscriptions with exclusive benefits.

Strengthen loyalty programs to push customers toward the Loyal segment.

Review discount policy for margin control.

Position top-rated and best-selling products in campaigns.

Target marketing toward high-revenue age groups and express-shipping users.

Prerequisites

- Python 3.x with pandas and a PostgreSQL driver (e.g., psycopg2 or SQLAlchemy).
- PostgreSQL server accessible to store and query the cleaned dataset.
- Power BI (or Power BI Desktop) for the final dashboard.

Steps

- Open the Python notebook to review data cleaning steps and how the cleaned data is loaded into PostgreSQL.
- Run the SQL analysis scripts to reproduce the business questions and results.
- Connect Power BI to the PostgreSQL database and import the cleaned tables or views to recreate the dashboard visuals.
- Review the PDF report for a narrative of findings and recommendations.

Project notes

The notebook demonstrates a practical, end-to-end workflow from raw data to analytics-ready data, with explicit attention to data quality and reproducibility.

The PDF consolidates workflow steps, analyses, and business-driven recommendations, serving as a ready-made companion to the notebook.

Contribution guidelines

If you extend the dataset or add new analyses:

Update the notebook with any new cleaning steps and data loading logic.

Create new SQL queries or views to capture additional insights.

Refresh the Power BI dashboard to reflect new metrics and visualizations.

Document any schema changes and provide migration notes to keep the PostgreSQL side in sync.


Contact
- My chariow store: https://wfzwxbem.mychariow.shop/
- My Facebook: https://www.facebook.com/share/1A5rXdCxQx/
- My LinkedIn: https://www.linkedin.com/in/peace-lwanzo-b862b51a6/
- My Instagram: https://www.instagram.com/peacelmpw?igsh=MWV0dTMzZXNjZ2oxcw== 
