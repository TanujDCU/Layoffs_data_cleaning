This project cleans and analyzes a dataset (2361 entries) of global company layoffs using MySQL. The goal was to take a messy, real-world dataset and prepare it for accurate analysis, then explore it to surface meaningful trends.

Data Cleaning:

Using MySQL, the raw dataset was cleaned in the following steps:

Removed duplicate records using window functions to identify and eliminate exact duplicate entries
Handled null and missing values, standardizing blank/null fields for consistent downstream analysis
Standardized inconsistent formatting across company names, industries, and date fields.

Exploratory Data Analysis (EDA):

With the cleaned dataset, further analysis was performed to uncover patterns:

Aggregated layoffs by company to identify which companies had the largest workforce reductions
Aggregated layoffs by industry to compare impact across sectors
Used ranking functions to identify the top 5 companies with the highest layoffs each year
