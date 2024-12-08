# Diwali Sales Analysis Using Python

Exploratory Data Analysis (EDA) is a fundamental aspect of data science, often taking up a significant portion of a data project. This repository demonstrates various EDA methods and techniques using Python, specifically applied to the Diwali Sales dataset sourced from Kaggle, which is ideal for EDA tasks. The aim is to gain deeper insights into sales data and enhance skills in data science. Good luck with your EDA journey using the Diwali Sales dataset.
This project focuses on understanding customer behavior, identifying trends, and analyzing sales patterns during the Diwali season using sales data. The process involves data cleaning, transformation, and visualization.

# 1. Importing Libraries
The libraries used in this project include:

Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Seaborn: For creating statistical visualizations.
Matplotlib: For building visualizations like bar charts and line graphs.

# 2. Reading the Dataset
The dataset is loaded using the Pandas library, with special encoding applied to handle any non-standard characters in the file. This ensures proper reading of data.

# 3. Dataset Overview
The dataset is reviewed to:

Check its dimensions (number of rows and columns).
Preview the first few rows of data to understand its structure.
Identify missing values and check the data types for all columns.
Get an overall summary of the dataset using metadata like column names and types.

# 4. Data Cleaning
4.1 Dropping Unnecessary Columns
Unwanted columns, such as Status and unnamed1, are removed as they do not contribute to the analysis.

4.2 Handling Missing Values
Any rows with missing values are dropped to ensure clean and reliable data for analysis.

4.3 Data Type Conversion
Columns like Amount, initially stored as strings or floats, are converted to integers to facilitate accurate numerical analysis.

# 5. Exploratory Data Analysis (EDA)
5.1 Gender Analysis
Visualized the distribution of buyers by gender and analyzed their spending.
Insight: Females not only dominate the buyer pool but also exhibit higher purchasing power compared to males.

5.2 Age Group Analysis
Explored purchasing trends across different age groups and their spending behavior.
Insight: The 26–35 age group makes the highest number of purchases and spends the most.

5.3 State-wise Analysis
Identified the top states based on the number of orders.
Insight: Uttar Pradesh and Maharashtra lead in order volume.

5.4 Marital Status and Gender Analysis
Compared spending behavior across marital statuses and genders.
Insight: Married females are the most significant spenders.

5.5 Occupation Analysis
Examined buyer occupations to identify which professions contribute the most to sales.
Insight: Buyers from IT, Healthcare, and Aviation sectors are the primary customers.

5.6 Product Category Analysis
Investigated the popularity of different product categories based on the number of orders and revenue.
Insight: Food items are the most frequently purchased and generate the highest revenue, followed by clothing and electronics.

5.7 Top Products
Identified the top 10 most sold products to understand customer preferences.
Insight: The analysis highlighted the most in-demand products.

# 6. Conclusion
The analysis revealed the following key insights:

Married females aged 26-35 years are the top buyers.
Customers from Uttar Pradesh and Maharashtra dominate purchases.
Most buyers work in IT, Healthcare, and Aviation.
Food, clothing, and electronics categories drive the highest sale
