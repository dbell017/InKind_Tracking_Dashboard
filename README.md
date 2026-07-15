# In-Kind Tracking

## Tools Used
- Python (pandas, numpy)
- PostgreSQL
- Tableau

## Key Features
- Parameter-driven filtering across 8 funding sources
- PostgeSQL queries to identify incorrect data
- Automated data cleaning reducing manual prep time

## Workflow
1. Data exported as CSV from database
2. Python (Jupyter Notebook) used to clean and standardize CSV for Tableau
3. PostgreSQL queries used to identify erroneous rows, 
   which are corrected directly in the source database
4. Corrected data re-exported and dashboard refreshed

## Overview
This project is used to track In-Kind dollar matches for several funding sources in Early Childhood Education (ECE) programs in a non-profit organization. 
In-kind contributions are goods or services donated by third parties (e.g., parents, businesses, and community representatives) that directly benefit the ECE programs. These contributions have a measurable value and can be counted toward the program’s non-federal share requirement.
The main dashboard (built in Tableau) includes crosstab visualizations that indicate category-specific dollars by month, as well as a parameter that be used to switch funding categories on the fly.
Primary KPIs being tracked are dollar amounts and percentages currently reached and remaining amounts left to reach yearly goals, which are a requirement of funders. 

Also included in this project is a Python cleaning script (Jupyter Notebook) that is used to clean and standardize the dataset in a CSV that is downloaded from the database.  
