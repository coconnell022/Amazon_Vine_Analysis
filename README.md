# Amazon_Vine_Analysis

## Overview of the Analysis

The purpose of this project was to conduct an analysis on a dataset that contains reviews of a specific product, in this case, shoes from Amazon. The dataset contains information regarding shoe reviews conducted on amazon by members of the paid Amazon Vine program, which provides members with the product so they are required to publish a review. The dataset that was provided by Amazon contains all information pertaining to the product reviews such as customer info, product info, review text, date, etc. The dataset was extracted and transformed, connected to an AWS RDS instance, and loaded into pgAdmin for analysis. Pandas was also used to determine if there were any bias towards favorable reviews from the Vine members throughout the dataset. 

    Resources
        - Data Sources: amazon_reviews_us_Shoes_v1_00.tsv
        - Software: Google Colab, AWS, PySpark, VS Code, Jupyter Notebook, pgAdmin 4

## Results
![alt text](https://github.com/coconnell022/Amazon_Vine_Analysis/blob/main/Images/Vine_df.png?raw=true)

How many Vine reviews and non-Vine reviews were there?
- There were a total of **22 Vine reviews** and **26,987 non-Vine reviews**

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Of all the 5-star reviews, **13 were paid Vine reviews** while **14,475 were un-paid non-Vine reviews**

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
-  Of the 5-star reviews, **59% were paid Vine reviews** and **54% were un-paid non-Vine reviews** 


## Summary



        Caroline O'Connell
        January 31st, 2021

