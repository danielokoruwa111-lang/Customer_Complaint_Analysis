# Customer Complaint Analysis
## Introduction
This Analysis is to identify and understand consumers complaint and how to rectify them.
## Data
This dataset was gotten from [Kaggle](https://www.kaggle.com/). This dataset consists of 13 columns and 75513 rows. The kind of information found in the table includes:
Complaint Details, Product and Issue, Company Information, Consumer Information, Submission and Response.
I read the above info from the dataset using:
```import pandas as pd
df = pd.read_excel('Financial Consumer Complaints.xlsx')
df.head()```
## Data Cleaning
I performed a data quality check to ensure it is clean and ready for analysis. These were the data issues I found and rectified.
1. **Incorrect Data Types:**

**To Find Incorrect Data Types:**
I used: 
