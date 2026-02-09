# Chicago Crimes Analysis (2020 - 2024)
## Project Overview
This project analyzes the Chicago Crimes dataset from 2020 to 2024 to identify criminal patterns, peak crime hours, and geographical distribution. The goal is to provide insights that can assist in resource allocation and public safety planning.

### Team Contributions
Data Collection: Youssef Mohamed

Data Cleaning & Preprocessing:Mohamed shaikhoun (me)

Data Visualization: Tarek Farag

### Project Workflow
1. Data Collection
Collected over 1.2 million records from the official Chicago City API using Python.

Handled large data volumes by splitting requests into batches of 50,000 records to ensure stability.

2. Data Cleaning

Note: This phase was critical to ensure the accuracy of the spatial and temporal analysis.


Geographic Filtering: Removed rows with missing latitude or longitude values, as valid coordinates are essential for mapping crimes.


Handling Nulls: * Imputed missing values in arrest and domestic columns with False.

Filled missing location_description entries with the placeholder 'unavailable'.

Data Standardization:

Converted the date column from string format to a proper datetime object.

Standardized arrest and domestic columns into boolean data types for optimized processing.

3. Data Analysis & Insights

Temporal Trends: Identified that crime rates peak during summer months (June, July, and August).


Hourly Patterns: Analysis showed that the most dangerous evening hours are between 6 PM and 11 PM.


Common Crimes: "Theft" and "Battery" emerged as the top reported crime types.


Location Analysis: Most incidents occur in Streets and Residential areas.

### Technologies Used

Python: For data collection and cleaning.


Pandas & NumPy: For data manipulation.


Matplotlib & Seaborn: For creating visual insights.
