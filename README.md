
# Homicide Data Analysis

This repository contains a Python script that performs various analyses on homicide data from different countries. The data is sourced from a CSV file hosted on GitHub.

## Python libraries Used 

- `pandas`
- `matplotlib`
- `seaborn`
- `plotly`

## Data File (Link)

https://raw.githubusercontent.com/Rruhid/data/refs/heads/master/homicide_by_countries.csv

## Steps Performed

### - Data Loading and Preprocessing 

The data is loaded into a Pandas DataFrame.
The 'Rate' column is converted to integer type.
The 'Subregion' column values are cleaned by replacing 'Australia, New Zealand' with 'Aus,NZ'.

### - Sorting and Displaying Top Countries

The DataFrame is sorted by the 'Count' column in descending order.
The top 10 countries with the highest counts are displayed in a bar plot.

### - Grouping by Region and Subregion

The data is grouped by 'Region' and 'Subregion' to sum the counts.
Bar plots are created to visualize the counts by region and subregion.

### - Filtering Data by Year

The data is filtered to include only records from years after 2015.
The filtered data is grouped by 'Region', 'Year', and 'Subregion' to sum the counts.
A bar plot is created to show the counts by region and year.

### - Summing Rates by Region and Year

The data is grouped by 'Region' and 'Year' to sum the rates.
A bar plot is created to show the sum of rates by region and year.

### - Creating a Treemap

The data is grouped by 'Region', 'Year', 'Location', and 'Subregion' to sum the counts.
A treemap is created using Plotly to visualize the counts by region, year, location, and subregion.




