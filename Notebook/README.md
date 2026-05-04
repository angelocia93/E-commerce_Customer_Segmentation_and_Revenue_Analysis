Python Data Preparation

This folder contains the Python workflow used to clean, transform, and structure the data for Power BI.

The process includes:

The process starts with data cleaning and preprocessing to ensure consistency and reliability.
Multiple datasets are then merged into a unified table, creating a solid foundation for further analysis.
From this base, additional features are engineered, including revenue-related and time-based metrics.
The workflow also includes an RFM analysis to evaluate customer behavior, followed by segmentation using both RFM scores and K-Means clustering.
Finally, the data is aggregated into structured datasets, ready to be used in Power BI.

Outputs:

monthly_sales.csv → monthly revenue trends

category_sales.csv → product category performance

rfm_customers.csv → customer-level RFM metrics

segment_summary.csv → RFM segment aggregation

cluster_summary.csv → clustering-based customer segmentation

All outputs are exported as .csv files and are ready to be used in Power BI.
