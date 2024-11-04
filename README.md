# Autostyle-Sales-Performance-Analysis

### Problem Statement

This project is intended to analyse the data of a Nigerian Car sales business, Autostyle Limited, and identify actionable insights and recommendations to help the business thrive. The analysis is intended to help the business and their different branches understand their customers better, their vehicle preferences and streategies to help them make more sales. Also, the analysis helps the business understand its customer demographic and their preferences to boost sales.


### Objectives set by the Client for the Analysis

- Analyze the performance of our branches. identify areas with the highest sales volumes, compare sales performance across branches, and understand regional preferences or market trends.
- Explore the preferences of our customers regarding car brands and models. identify the top-selling brands, analyze the popularity of different car models, and uncover any patterns in product preferences.
- Gain a comprehensive understanding of our customer base demographics. uncover insights into the age, gender, and other relevant characteristics of our customers.
- Dive deep into our sales performance over the course of 2020. identify trends in sales volume, uncover any seasonality effects, and pinpoint peak sales periods.

### Steps followed
Step 1 : Load data into Microsoft Excel Power Query, dataset is an Excel file. There are 1491 Rows and 6 Columns of data in the dataset.

**Original Dataset for Analysis**

![image](https://github.com/user-attachments/assets/da0dd31b-a80f-4f04-ae77-2b37236e6335)


Step 2 : Cleaned the data by:
- Trimming leading and trailing spaces.
- Replaced inconsistent data.
- Replaced outlier data with the median value.
- Split Model column into car model and car brand for the purpose of analysis.
- Created an age range column using the age column for analysis
- Changed relevant data.
- Created a calendar table with the date column to extract the Year, Month, Quarter, Day columns and removed duplicates to create relationship between the two tables.


Step 3 : Closed and Loaded the cleaned data into Excel for Analysis

**Cleaned Dataset for Analysis**

![image](https://github.com/user-attachments/assets/7c4b7692-4179-4c90-a9ff-01ac74701368)

**Newly created Calendar Table Dataset for Analysis**

![image](https://github.com/user-attachments/assets/0135e9b8-68dd-4b36-94e7-bceaf3ef3c7c)

Step 4 : Loaded both tables into Power Pivot and created an entity relationship using the date column for ease of analysis.

![image](https://github.com/user-attachments/assets/4996b35f-48d0-43c9-a9bb-094bf32feccb)


Step 5 : Created multiple DAX Formulas; pivot tables to analyse the data and gain actionable insights. This pivots and insights data were extracted to create dashboard.

Step 6 : [View dashboard, insights and recommendation](https://github.com/olubadero/Autostyle-Sales-Performance-Analysis/blob/main/insights.md)

