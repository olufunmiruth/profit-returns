# profit-returns
The Excellent Store Challenge by Data Science Nigeria,Predict profit returns per product per outlets.This is a private hackathon open to Data Science Nigeria (DSN) Pre-Bootcamp hackathon participants

Babatunji Stores, popularly known as “The Excellent Store”, is a leading indigenous chain of stores with headquarters in Gbagi, Oyo, Nigeria. At the core of their business is a strong sense of excellence and entrepreneurial value. And this is evident in all their 1,500 products, available to all segments of the population at customer-friendly prices, across 10 stores in different cities of Nigeria.
The CEO of the company, Chief A. A. Babatunji, plans to expand the chain of stores to more Nigerian cities in 2021. However, as the COVID19 restrictions have affected the retail business, he sees the need to better understand which products return higher profits at specific stores so as to inform the expansion plan.
You have been engaged as the new Retail Data Analyst to build a predictive model and find out the profit returns on each product at a particular store. The scenario he sees is where a brand of juice sold for N250 in one of his store branches may also be sold at N230 at another store within Chief Babatunji's chain of stores. He needs to therefore understand what type of product, market clusters and store type (location, age, size) will give more profit returns as he plans to expand to more cities in the country.
From your predictions, Chief Babatunji will understand the key characteristics of items and stores, which drive returns and have better insight on how to proceed with the plan of expansion.
ou have been provided with transactional records of all the stores at product level. Due to power failure and technical glitches, some stores might not report all data, hence the data may have missing values.

Variable Description
    -Item_ID: Unique product ID
    
    Item_Weight: Weight of the product
    
    Item_Sugar_Content: Sugar content of the product
    Item_Visibility: The percentage of total display area of all products in Chief Babatunji’s supermarket allocated to the particular product
    Item_Type: The category to which the product belongs
    Item_Price: Retail price of the product
    Store_ID: Unique store ID
    Store_Start_Year: The year in which store was opened
    Store_Size: The size of the store in terms of total ground area covered
    Store_Location_Type: The type of city in which the store is located
    Store_Type: Description of the store based on category of items sold
    Item_Store_ID: Unique identifier of each product type per supermarket.
    Item_Store_Returns: Profit returns on the product in the particular store. This is the outcome variable to be predicted.

The evaluation metric for this challenge is Root Mean Squared Error. Values can be any number.
