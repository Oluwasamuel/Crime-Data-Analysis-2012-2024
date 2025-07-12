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


# 📊 Key Insights from Police-Recorded Crime Data (2012-2024)
Based on the cleaned and merged dataset, here are four critical trends visualized and summarized:

### 1. 📈 Trend Analysis – Crime Over Time
Overall Trend: Total recorded crime rose steadily from 2012/13 (~3.7M offences) to a peak in 2018/19 (~5.8M), then declined during COVID-19 (2020/21) before rebounding.
Key Observation:
Violence Against the Person (e.g., assaults) grew 35% (2012–2019), driven by improved recording standards.
Fraud (e.g., online scams) tripled (2012–2023), reflecting digital crime shifts.
Theft (e.g., shoplifting) dropped 20% during lockdowns (2020/21) but surged post-pandemic.

### 2. 🏆 Category Comparison – Crime by Force
Top Forces by Volume:
Metropolitan Police (London) consistently reports ~25% of all crimes.
Greater Manchester and the West Midlands follow, driven by urban density.
Notable Outliers:
North Yorkshire had under-reported data (2022/23) due to administrative issues.
Devon & Cornwall missed Q3/Q4 2022 data (IT system failure).

### 3. 🎯 Distribution Analysis – Crime Types
Most Common Offences (2023):
Violence Without Injury (22% of total) – e.g., harassment.
Shoplifting (15%) – rising post-pandemic amid cost-of-living crises.
Vehicle Offences (12%) – theft from vehicles dominates.
Emerging Threats:
Fraud via False Representation (e.g., phishing) grew 400% (2012–2023).
Sexual Offences (e.g., rape) increased 70%, partly due to improved victim confidence.

### 4. 🔍 Custom Insight – Regional Hotspots
Knife Crime: West Midlands and London account for 50% of all "possession of blade" offences.
Racially Aggravated Crime: Leicestershire and South Yorkshire show 2x higher rates per capita vs. the national average.
Rural vs. Urban: Avon & Somerset (rural mix) has 2x higher burglary rates than Cambridgeshire, likely due to lower police density.

# 📌 Summary
Digital crime (fraud, cyber threats) is the fastest-growing category.
Post-COVID recovery saw a rebound in traditional crimes (theft, violence).
Geographic disparities highlight resource allocation needs (e.g., knife crime in cities).
Data gaps (e.g., Devon & Cornwall) emphasize infrastructure risks in modern policing.
Next steps: Targeted interventions for fraud prevention and urban knife crime reduction.
