# citibike-marketing-analytics 🚲

## Introduction

The Citibike Marketing Analysis project aimed to enhance revenue and customer satisfaction for Citibike through a meticulously crafted marketing plan. Utilizing over 10GB of public data from Citibike's website, the project employed temporal sampling to manage the dataset efficiently, maintaining its distribution while reducing its size. To boost revenue, the analysis identified potential new station locations in NYC/NJ by analyzing customer segments and pinpointing areas with similar characteristics to high-performing segments. To increase customer satisfaction, a rebalancing strategy for existing stations was developed, using the PageRank algorithm to determine central stations within the network for optimal bike availability. This strategic approach combined data analysis with actionable marketing tactics to address the project's objectives.

## Dataset Source: https://citibikenyc.com/system-data
## File & Folder Description:
data_compilation.ipynb: Used to compile the seperate monthly data to create a compiled dataset for 2 years.
data_sampling.ipynb: Used to sample the collected data. (Temporal Stratified Sampling)
data_cleaning.ipynb: Used for preliminary cleaning of the data.
feature_engineering.ipynb: Used to create new features based on the existing features in the dataset.
marketing_analysis.ipynb: Used to conduct marketing analysis and extract findings displayed in the presentation.
final_data_cleaned.csv: CSV file extracted after all the data preprocessing and feature engineering steps.
network_map.png: Complete network graph generated by Page Rank.
Folder-> data: Contains .csv files for the data sourced from the citibank source.

## Report
The PDF report with all the findings and recommendations can be access through the file "Marketing_Report.pdf".

## Resources:
https://citibikenyc.com/system-data/operating-reports: Maintainence and Repair Costs & Product, Pricing and Placement Details
https://www.nyc.gov/site/buildings/index.page: Permit fees and Requirements
https://ride.citibikenyc.com/blog/major-citi-bike-expansion-map-revealed: Simmilar Projects on Expansions

**Important Note:** In this repository, I have not included all the separate .csv data files for each month. The link mentioned in the dataset source can be used to access all the data files. However, the final data on which the analysis was performed (final_data_cleaned.csv) is provided.
