Retail Sales Data Analysis — Advanced Pandas Project

This repository contains an end-to-end *Retail Sales Analysis* project built using *Python Pandas*.  
The project demonstrates strong capabilities in *data cleaning, manipulation, time-series analysis, window functions, merging operations,* and *handling large datasets* — all essential skills for a Data Analyst role.


Project Overview
Retail businesses generate large volumes of transactional data.  
This project analyzes such data to uncover insights about:

- Customer purchasing patterns  
- Category-wise and region-wise sales  
- Monthly revenue trends  
- Product performance  
- Demographic insights  

The focus of this project is *Pandas-only analysis*, showcasing advanced data manipulation techniques.


Dataset Fields

| Column | Description |
|--------|-------------|
| Order_ID | Unique order number |
| Date | Order date |
| Product | Product purchased |
| Category | Product category |
| Quantity | Items purchased |
| Price | Price per unit |
| Customer | Customer name |
| City | Location |
| Region | Geographic region |
| Age | Age of customer |
| Gender | Gender of customer |

Additional field created:
Sales = Quantity * Price


Key Pandas Features Implemented

1. Data Cleaning
- Fixing data types  
- Handling null values in Price/Quantity  
- Removing duplicates  
- Cleaning inconsistent categorical values  

2. Feature Engineering
- Sales column  
- Adding Region  
- Converting object → category  
- Reordering category levels  
- Multi-level sorting  

3. GroupBy Operations
- Total sales by category  
- Sales by region  
- City-wise performance  
- Customer segmentation  

4. Pivot Tables
- Category vs Region  
- Gender vs Product quantity  
- Monthly Sales reports  

5. Merging & Joins
- Left, Right, Inner, Outer joins  
- Customer table merge examples  
- Error handling with mismatched keys  

6. Window Functions
- Rolling average (moving average)  
- Cumulative sales  
- Expanding window metrics  

7. Time Series Analysis
- Date parsing  
- Setting Date as index  
- Monthly resampling  
- Trend detection  

8. Data Reshaping
- stack() and unstack()  
- melt() for long format  
- MultiIndex operations  

 9. Apply Functions
- Row-wise calculations  
- Lambda transformations  
- Custom functions  

 10. Vectorization
- Fast column operations without loops  
- NumPy integrated calculations  

