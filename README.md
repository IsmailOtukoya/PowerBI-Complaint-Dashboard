# Power BI Complaints Dashboard
## Overview
This repository contains a Power BI dashboard designed to analyze and visualize customer complaints data. The dashboard helps businesses monitor and improve their customer service by providing insights into key metrics such as average resolution time, complaint distribution by category, and the proportion of resolved vs. unresolved complaints.

## Dashboard Features
Average Resolution Time: Shows the average number of days taken to resolve complaints.
Total Complaints by Category: Visualizes the number of complaints across various categories like Service, Technical Support, Product Quality, Delivery, and Billing.
Resolution Status Distribution: Displays the proportion of complaints that are resolved versus unresolved.
Complaint Trends Over Time: Tracks the average resolution time over the course of the year.

## Explore the Dashboard:
Interact with the visuals by using the slicers to filter data by date, category, and resolution status.
Hover over charts and graphs to see detailed tooltips and insights.
Data Cleaning & Transformation

The original dataset was preprocessed and cleaned using Python before being imported into Power BI. Below is an outline of the key steps:

## Data Cleaning:
## Handling Missing Values: 
Missing data in key columns were filled using appropriate methods (e.g., using the mean for numerical data or the mode for categorical data).
## Outlier Detection: 
Outliers in the resolution time were identified and managed to avoid skewing the analysis.
## Data Type Conversion: 
Ensured all columns had the correct data types (e.g., converting date columns to datetime format).
## Data Transformation:
## Feature Engineering: 
Created new features, such as Resolution Ratio, which is the proportion of resolved complaints to total complaints.
Data Aggregation: Aggregated data by category and date to provide meaningful insights at a higher level.
## Normalization: 
Normalized certain columns to bring them onto a comparable scale.
The Python script used for this process is included in the repository as data_cleaning_and_transformation.py.

# Key Insights
Resolution Efficiency: The average resolution time was found to be 12.4 days, with the month of July showing the highest resolution time, indicating possible seasonal challenges or increased complaint complexity.
Complaint Distribution: The most common categories for complaints were Service and Technical Support, highlighting areas where the company could focus on improving customer satisfaction.
Resolution Success Rate: Approximately 81.3% of complaints were resolved, leaving about 18.7% unresolved. This indicates a need for a more robust resolution process.
Repository Contents
Complaints_Dashboard.pbix: The Power BI dashboard file.
dataset/: Folder containing the raw and cleaned datasets.
data_cleaning_and_transformation.py: Python script used for data cleaning and transformation.
README.md: This document, providing an overview of the project.
# Contact
If you have any questions or feedback, feel free to reach out via GitHub or LinkedIn.
