# Analysis-and-Visualization-of-Sales-Data
Overview
This project provides an interactive and visually rich dashboard for analyzing sales data from a retail superstore. Built using Streamlit and Plotly, the dashboard allows users to explore sales trends, filter data by various criteria, and visualize insights in multiple formats such as bar charts, pie charts, line graphs, and treemaps.

Features
Date Range Selection: Filter data based on the order date.
Region, State, and City Filtering: Drill down into specific geographic areas.
Category-wise and Region-wise Analysis: Visualize sales distribution using bar and pie charts.
Time Series Analysis: Explore monthly sales trends over time.
Hierarchical View: View sales distribution across regions, categories, and sub-categories using treemaps.
Segment-wise and Sub-category-wise Analysis: Detailed visualizations for sales by customer segments and sub-categories.
Sales and Profit Correlation: Scatter plot showing the relationship between sales and profit.
Downloadable Data: Export filtered and aggregated datasets as CSV files.

Installation
Clone this repository or download the files.
Install Python (3.7 or higher) and the required libraries:
pip install streamlit pandas plotly
Place the dataset (Superstore1.csv) in the same directory as the script.

Usage
Run the dashboard using Streamlit:
streamlit run Dashboard1.py
Upload a CSV file through the dashboard or use the default dataset (Superstore1.csv).
Interact with the filters and visualizations to explore the data.

Dataset
The provided dataset contains sales data with the following key attributes:
Order Date: Date of the transaction.
Region, State, City: Geographic location details.
Category, Sub-Category: Product classification.
Sales, Profit: Financial metrics.

Visualizations
Category-wise Sales: A bar chart comparing sales across product categories.
Region-wise Sales: A pie chart showing sales distribution across regions.
Time Series Analysis: A line chart of monthly sales trends.
Hierarchical Treemap: A multi-level visualization of sales by region, category, and sub-category.
Scatter Plot: Displays the correlation between sales and profits.
Summary Tables: Pivot tables and formatted views for quick insights.

Data Export
Filtered and summarized data can be downloaded in CSV format directly from the dashboard.
