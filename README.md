# Crime Data Analysis, Data-Cleaning-Merging-Visualization-2012---2024-
Police recorded crime Police Force Area Open Data tables, from year ending March 2013 to year ending June 2023
Crime Data Analysis 2012-2024
This repository contains a data analysis project focused on crime data from 2012 to 2024. The project aims to clean, merge, and visualize crime data to uncover key insights and trends. Data Source: The data used in this project originates from the UK Home Office's Police Recorded Crime Open Data Tables, covering the period from the year ending March 2013 to the year ending June 2023. For more details about the data, refer to the official documentation: Police Recorded Crime and Outcomes Open Data User Guide.

#Data Cleaning
### Remove Duplicates:
Duplicate rows were identified and removed from the dataset using specific columns (e.g., "Financial Year," "Police Force Name," "Offense Description," and "Crime Count") to ensure data uniqueness.
### Handle Missing Values:
For numerical columns like "Crime Count," missing values were filled with the column's average. For categorical columns such as "Police Force Name" and "Offense Description," missing values were filled with the most frequent value in the column.
### Ensure Consistency: 
Standardized data formats across columns (e.g., unified formats for "Police Force Name" and "Financial Year") to ensure data consistency.
### Data Merging:
The data from all sheets from 2012 to 2024 was consolidated into a single dataset using tools like Excel's Power Query. The merged dataset includes columns such as "Financial Year," "Police Force Name," "Offense Description," "Offense Group," "Offense Subgroup," and "Crime Count."

# Visualization
### Trend Analysis-Crime Financial Year:
A line chart showcasing crime trends over financial years. Reveals whether crime counts have increased or decreased over time.

### Category Comparison-Performance by Police Force and Offense Description: 
A clustered column chart comparing crime counts across different police forces and offense descriptions.
### Distribution Analysis: 
A stacked bar chart illustrating the distribution of crime counts across offense groups, offenses, and subgroups.
### Custom Insight:
A scatter plot analyzing the correlation between crime counts and financial years for specific police forces or offense descriptions.
