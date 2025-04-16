# Amazon Sales Ratings and Reviews

[Dasshboard link] https://public.tableau.com/app/profile/mohammad.al.hussein/viz/Amazon_Project_Product_Performance/AMAZONPRODUCT-CUSTOMERSATISFACTIONDASHBOARD

## Introduction
The primary goal of this project is to analyze the Amazon Sales dataset and identify insights based on the data. This  dataset is a valuable resource for businesses and researchers. It provides a great deal of information about customer behavior and interactions with products.
This will enable retailers, manufacturers and platform sellers to adjust their products and services to customer’s needs based on the information contained in the reviews thus ensuring better service and customer satisfaction that will drive higher sales.
This study identifies the most popular products in terms of number of listings , quality, actual, discounted prices , feedback and  final sentiments given to Specific Categories by customers.
The study does not include revenues estimation as no information was available about the number of items per specific category in the data .

## Business Impact

Exploring the dataset will help businesses to identify causes that contribute to higher product sales, a few factors are observed that could potentially drive sales up in each Specific Category:

 - The need and intended use of the product 
 - 	The quality of the product in terms of durability
 - 	The discounted price offered by vendors on products 

By analyzing the above and more, researchers and businesses alike can devise strategies to exploit the potential for better customer satisfaction thus achieving higher sales

## Data

- File Name: 		Amazon Sales Dataset
- Description:	1K+  of Amazon Product's Ratings and Reviews
- Dataset Details: 	1463 Rows and 19 Columns
- Size: 			2 MB
- Source: 		Kaggle
---
## Data Analysis & Computation

 Data Profiling:
-	Use excels filters to check duplicate values.
-	Investigate the total number of rows and columns (1463 Rows and 19 Columns)
-	Examine the data types of each column using data type functions on excel
-	Examine null values in all columns
-	Investigate unique values in each column

---
Observations:

-	The  empty column between review_content and Sentiment  was deleted, data types of columns : actual_price, discount_percentage, and rating_count have been converted and standardized to general number format.
-	Forty-one (41) duplicate values in all rows were found.
- The specific Category column had 8 blank rows out of 1464 amounting 0.5% of all rows , since percentage was low,  the blanks were removed.
- The sentiment , sentiment _name and Sentiment _Score columns had 80 % null values which can be filled with a pre-defined value of the mean and mode .
---
 Data Wrangling:

- Forty-one (41) duplicate rows were removed.
- Columns remined at 18 and the remaining rows  became 1413
- Columns:  about_product, user_id, user_name, review_id, review_title, review_content were ignored in the study as they only contained text values 
- One empty column was removed 
---
 Data Analysis:

1-	Most popular listings by Specific Category:
Judging from the chart below, the most popular Specific Category of products in the data set is Cables and Accessories with over 200 listings while the least popular in the same top 15 list  is water purifiers & accessories with approximately 25 listings.


![image](https://github.com/user-attachments/assets/6e124101-a541-4e1c-a690-b03db9187385)



2-	Actual VS Discounted price Distribution:
it was observed that the subcategory of  Air-conditioners has the most gap between actual and Discounted prices at around 40k of difference while External hard disks had the least price difference.

![image](https://github.com/user-attachments/assets/47846d14-c9b2-4257-8eb7-e033f9f24814)




 
3-	Average rating

.  
Investigating the rating of Product Specific category form the above chart, it was observed that most product ratings in the top 15 list fall between 4.3 and 4.5 with Cord Management, memory ,Surge Protectors, Streaming devices and Calculators sharing the lead at  4.5 while Air conditioners , Drawing & painting supplies cases and External Memory card reader are the lowest on then same list at a shred rating of 4.3.


![image](https://github.com/user-attachments/assets/de494b1f-bcaf-4fe8-8501-8fb9905e3314)



4-Sentiment Feedback (General)
From the Available 20 % of the total data on  Sentiment Feedback we can tell from the below Pie chart that in general 70 % of the feedback was positive and 19% was negative where neutral feedback is as low as 11%.


![image](https://github.com/user-attachments/assets/8af5e85a-d6f6-49f2-9ba9-d282783ebe85)


 

5-Correlation Analysis
•	The correlation between Discount price and Rating was plotted and calculated , a correlation coefficient value of 0.107 shows a weak positive correlation which indicates there is no relation between the discounted price and ratings.

![image](https://github.com/user-attachments/assets/64d0be8b-1cf7-42f1-90f7-11c8f6100f12)




•	The same was done for rating count and the discounted price, this correlation coefficient of -0.026 indicates a weak negative correlation which also shows no relation between the rating

![image](https://github.com/user-attachments/assets/28523a10-5a68-452f-92d2-aeef9696442a)






 ---

## Dashboard Description

The Dashboard’s intended purpose is to provide an interactive filtering system to allow readers to investigate each Specific Category in terms of popularity , rating , actual vs discounted price and general sentiment about the listings in the Dataset ,. The dashboard breaks down the dataset by the Specific Category against the above measures using the top 15 Specific Categories as an overall Product Performance Indicator.





![Dashboard_Main](https://github.com/user-attachments/assets/741ae56e-a4fb-4b5f-b7c9-cea9c8a5b066)






---

## Conclusion & Future Work

Conclusion:

The analysis conducted prove beyond doubt that the popularity of products is a combination  of 3 elements,  Serving the intended use, quality and the discount percentage applied to the actual price, ratings have no significant impact on the popularity of products.
Reviews and Sentiments provide a useful source of information for vendors so corrective measures  can be  taken to adjust products and services to customer’s needs and expectations. 




![Project_Datafolio](https://github.com/user-attachments/assets/a60d9856-8fe3-4175-9fb3-3177c706a321)



---


Future Work:

The missing 80% of the sentiment data values  could be compensated by generating values around the mode and mean to complete this relevant section of data as it provides important feedback and good insight for vendors about products and services.
Completing the Sentiment Values in the dataset would give more and better insight about the sentiment in relation to each Specific Category.

