# SuperStore Analysis: Marketing Insight Report

## Table of Content
   - [Project Overview](project_overview)
   - [Data Source](data_source)
   - [Tools](tools)
   -  [Data Cleaninig](data_cleaning)
   - [Exploratory Data Analysis (EDA)](exploratory_data_analysis_(EDA))
   - [Data Analysis](data_analysis)
   - [Data Insights](data_insights)
   - [Recommendations](recommendations)
   - [Conclusion](conclusion)

## Project Overview
    The dataset contains important performance metrics like total revenue, total profit, and total quantity sold.
    This analysis's objective is to find significant patterns, trends, and anomalies that could offer useful information
    for marketing and business strategy.

![image](https://github.com/user-attachments/assets/92c27adb-5a43-46df-8f32-fea09eb926d9)


### Data Source 
    This dataset is from Kaggle website
    The dataset includes:
    1.  Categories:
        -  Technology
        -  Furniture
        -  Office Supplies
    2.  Sub-Categories:
        -  Phones	
        -  Storage
        -  Tables
        -  Machines
        -  Furnishing
        -  Paper
        -  Supplies etc.
    3.  Regions:
        -  Central
        -  South
        -  East
        -  West
    4.  Shipping Modes:
        -  First Class
        -  Second Class
        -  Same Day
        -  Standard Class
    5.  Customer Segments:
        -  Consumer
        -  Corporate
        -  Home Office

### Tools 

    Power Query for Cleaning
    Power Bi for visual and analysis

### Data Cleaning 

    -    Removed duplicates and null values.
    -    Ensured consistency in text columns 
    -    Converted date columns to proper datetime format if applicable.
    -    Ensured numeric columns like sales, profit, and quantity contain only valid values (i.e no negative sales)

### Exploratory Data Analysis (EDA)

    1.    What is the total revenue, profit, and quantity sold?
    2.    Which product categories contribute the most to total sales and profit?
    3.    What are the most and least profitable sub-categories?
    4.    Which sub-categories generate the highest and lowest revenue?
    5.    Which region (East, West, Central, South) has the highest sales and profit?
    6.    Which shipping mode is most commonly used?
    


### Data Analysis

  -  Top-performing sub-categories:
      -  Phones contribute the highest sales at ($330.01), followed by storage ($223.84) and Tables ($206.97).
      -  Machines ($189.24K) also perform well.
  -  Least-performing sub-categories:
      -  Fasteners with a record of ($3.02) and labels as ($12.49) have the lowest sales, indicating potential low demand or pricing strategy concerns.

### Data Insight

1.  Sales Analysis
      -  From the analysis, total revenue generated is $2,297,201, total profit of $286,397, and total quantity sold is 37,873 units.
      -  From the category session, the technology category leads in sales with $836,154, followed by furniture ($742,000) and office supplies ($719,047).
      -  Despite having reasonable sales volumes, some subcategories report negative profit, such as Tables (-$17.7 profit) and Supplies (-$1.18 profit).

2.  Region with the most sales:
      - Sales are split fairly evenly between the regions, with the East and West exhibiting the best revenue results.
      - Out of the four regions we have in the dataset, the South region exhibits the lowest revenue, suggesting possible areas for growth tactics.

3.  Mode of Shipping Products: 
      -  Same Day shipping contributes the least ($128,363) to sales, while Standard Class shipping leads with $1,358,216.
      -  First Class and Same Day expedited shipping options are used less frequently, perhaps as a result of customer preferences or financial concerns.
    
4.  Trends on Profit:
      -  With the high revenue, certain sub-categories like tables and bookcases show negative profit margins, indicating  that high discounting could be
         affecting profitability.
    
5.  Trends on Discount:
      -  The average discount rate is 15.6%, and some sub-categories like Tables (26.1%) and Bookcases (21.1%) receiving high discounts.
    
### Recommendations

    -  High discount rates have an effect on the profitability index of some high-revenue categories. Reevaluating discounting 
       tactics may increase profits.
    -  Increasing sales in high-performing categories such as phones, storage, and machinery could result in even higher sales.
    -  Management should address negative profit margins: Sub-categories such as Table, Supplies, show loss
    -  Sales should be improved in underperforming regions, such as the South region, and the management should target marketing 
       efforts to be put in place to enhance overall revenue distribution.
    -  As it was analyzed that Standard Class shipping is the most popular option, management  should consider offering incentives 
       for expedited shipping in order to improve customer satisfaction.

### Conclusion

    The insight gained from superstore analysis can improve business performance by increasing profitability, optimizing 
    product offerings, and honing marketing strategies.



