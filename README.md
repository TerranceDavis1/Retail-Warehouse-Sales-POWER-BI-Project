# Retail-Warehouse-Sales-POWER-BI-Project

# Warehouse & Retail Sales Analysis

### Dashboard Link : https://app.powerbi.com/links/E8sup8kCag?ctid=4278a402-1a9e-4eb9-8414-ffb55a5fcf1e&pbi_source=linkShare&bookmarkGuid=a086f9e8-a3b9-4cd9-a3c8-4f990a3d7c1a

blob:https://app.powerbi.com/45270692-5461-4ffa-a035-676b6333ffb9

## Introduction

This dashboard explores retail sales and warehouse sales trends across various item types and suppliers, providing insights into business performance and opportunities for growth. This project utilizes Power BI to visualize and analyze sales data, identifying key trends and patterns in item type sales, supplier performance, and yearly performance. The analysis reveals top-performing item types, suppliers, and time periods, and provides recommendations for future business decisions. By examining the relationships between sales data, item types, and suppliers, this project aims to inform business strategy and optimize sales performance, ultimately driving business growth and improvement.


### Steps followed 

- Data Cleaning:
Removed all blank rows and columns from the dataset to ensure data consistency and reduce unnecessary data.
Cleaned the text in the ITEM Description column to ensure that only printable characters were present, improving data quality and readability.

2. Error Handling:
* Addressed the [DataFormat.Error] issue by identifying and resolving data formatting errors, ensuring that the data was in a suitable format for analysis.
3. Column Modification:
* Removed the original Month column, as all values were identical (1), and replaced it with a custom column called MONTH with values ranging from 1 to 12, allowing for better representation of data variability.
4. Data Type Conversion:
* Changed the data type of the Retail Sales column from decimal to whole number, removing all rows with 0 values to improve data accuracy and relevance.
* Changed the data type of the Retail Transfers column from decimal to whole number, ensuring consistency in data formatting.
5. Data Filtering:
* Removed all rows with 0 values in the Warehouse Sales column, filtering out unnecessary data and improving data quality.
* Changed the data type of the Warehouse Sales column from decimal to whole number, ensuring consistency in data formatting.
6. Text Processing:
* Split and delimited the ITEM Description column to remove numbers and "oz" values, enabling easier data export and analysis.
* Removed all hyphens (-) from the ITEM Description column for visual purposes, improving data readability.
8. Data Reduction:
* Kept only the first rows of data and removed over 1000 rows to reduce data complexity and improve analysis efficiency.
9. Column Replacement:
* Removed the original Year column, as all values were identical (2020), and replaced it with a new Year column with values ranging from 2012 to 2024, providing a more comprehensive and varied dataset.

 

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

 

### Item Type
    1.1)   Liquor has the most retail sales (2k)
    1.2)   Beer has the most Warehouse sales (5k)
    1.3)   Liquor had the most Retail transfers (retail to warehouse) (2084)
    1.4)   Liquor leads in sales for item types in 2020, 2021, 2022, and 2023
    1.5)   Beer leads in sales for item types in 2024
 

 
 ### Supplier
 
    2.1)  Jim Beams sold the most in retail out of all suppliers (842)
 
    2.2)  Legends LTD sold the most in warehouse sales (642)
 
    2.3)  Sutter Home Winery led in retail sales in November 2020
 
    2.4) Mark Anthony Brands INC led in warehouse sales in January 2021 (268 sales)
 
    2.5) Jim Beams led in retail sales in 2022 (332 sales)
    
    2.6) Miller Brewing company led in warehouse sales in 2023

    2.7) Heinken led in warehouse sales in 2024


### Warehouse Sales

    3.1) 2022 had the most Warehouse sales of the combined item types

    3.2) 2023 Warehouse sales outperformed retail sales, specifically in June with 296 sells
       
    3.3) 2021, January, had the most warehouse sales in that year

    3.4) 2024 Warehouse sales leads, July most warehouse sales with 236
    

### Retail Sales

    4.1) 2022 had the most retail sales of the combined item types

    4.2) 2020 had the largest proportion of retail sales with 3504

    4.3) 2020 in November, retail sells out performed every statistic

### Creator
    Terrance Davis
    Email: tldavisj@syr.edu
    Linkedin: www.linkedin.com/in/terranceldavis
 
    
### Source
    Orginal Dataset & Creator: 
    Dataset - https://www.kaggle.com/datasets/divyeshardeshana/warehouse-and-retail-sales
    Creator - Divyesh Ardeshana
 
### Key Note
To view in excel, make sure you have connected to the dashboard. Either download the dashboard or ensure that you're connected to the dashbaord to do this.
