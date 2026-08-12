# Customer Churn Analysis and Customer Intelligence

## Project Overview

This project analyzes customer churn to extract valuable customer intelligence and identify effective retention strategies. It involves a comprehensive data pipeline from raw data ingestion to advanced visualization.

## Key Functions and Analysis Steps

The project encompasses the following major functions and analysis steps:

1. **Data Import and Database Creation**: Importing raw customer data from an Excel file and converting it into a structured SQLite database with distinct tables for customer, subscription, and support information.
2.  **Data Cleaning and Preprocessing**: Thorough cleaning of each dataset, including column renaming, handling missing values, standardizing data formats (e.g., gender), correcting data types for dates, and resolving duplicate entries.
3.  **Feature Engineering**: Creating new insightful features like `churn_flag` and `churn_risk` to enhance analytical capabilities.
4.  **Data Merging**: Consolidating customer, subscription, and support data into a single, unified DataFrame for holistic analysis.
5.  **Key Performance Indicator (KPI) Calculation**: Deriving critical business metrics such as Churn Rate, Retention Rate, Average Revenue Per User (ARPU), Average Customer Tenure, Revenue at Risk, Escalation Rate, and Correlation between Escalations and Churn.
6.  **Data Visualization**: Creating various plots and charts using Matplotlib and Seaborn to visualize churn trends, rates by plan type and state, correlation heatmaps, and multi-dimensional comparisons.
7.  **Pivot Table Analysis**: Utilizing pivot tables to aggregate and summarize data, providing insights into plan-type performance regarding churn, monthly charges, and customer counts.
8.  **Data Export**: Exporting the cleaned and processed dataset to a CSV file (`exported_churn_data.csv`) for potential use in external business intelligence tools like PowerBI.

## Technologies Used

*   **Programming Language**: Python
*   **Data Manipulation and Analysis**: `pandas`, `numpy`
*   **Database Management**: `sqlite3` (for SQLite database creation and interaction)
*   **Data Visualization**: `matplotlib.pyplot`, `seaborn`
*   **Business Intelligence**: The cleaned dataset (`exported_churn_data.csv`) is prepared for integration with PowerBI dashboards.

## How to Run

1.  **Place Data File:** Ensure `customer_churn_data_raw.xlsx` is in the same directory as the notebook.
2.  **Open in Google Colab:** Upload and open `churn_analysis.ipynb` in Google Colab.
3.  **Run Cells:** Execute all cells sequentially. The notebook will automatically convert the Excel file to an SQLite database and perform all subsequent analysis and visualizations.
