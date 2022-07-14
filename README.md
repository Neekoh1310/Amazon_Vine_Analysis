# Amazon_Vine_Analysis

## Project Overview
In this project, I was tasked to analyze the Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Resources
- Google Colab, Data (50 sets of Amazon Reviews), PySpark, Amazon Web Services (RDS, S3), PostgreSQL, pgAdmin4

# Analysis
<p>I decided to use the Wireless_v1_00 Amazon Reviews for this analysis. In order to start the analysis, I had to load the data using Google Colab and PySpark:</p>

![Screen1](https://user-images.githubusercontent.com/102476861/179003855-404ab0dd-466e-461d-b261-8c8209486f84.png)


### Results
<p>
  
1.) How many Vine Reviews and Non-Vine Reviews were there?
  - Total Vine Reviews: 613
  - Total Non-Vine Reviews: 64,968
  
2.) How many Vine reviews were 5 stars? How many Non-Vine reviews were 5 stars?
  - 5 Star Vine Reviews: 222
  - 5 Star Non-Vine Reviews: 30,543
  
3.) What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - 5 Star Vine Reviews Percentage: 36.22%
  - 5 Star Non-Vine Reviews Percentage: 47.01% 
</p>
  
![Vine Reviews](https://user-images.githubusercontent.com/102476861/179001778-fa2a27e4-5165-4277-80c9-a9d30e1b9a57.png)

## Analysis

<p>Looking at these results, the difference between the number of Vine and Non-Vine reviews is staggeringly huge, but the 5 Star Review Percentage tells a different story. The Vine Reviews actually have a smaller percentage of 5 Stars than the Non-Vine one, which shows that in this particular set of reviews, positivity bias does not exist. If the results were flipped (Vine Reviews > Non-Vine Reviews), then a positivity bias can be postulated. 

However, this is just one set of reviews. To more accurately determine whether positivity bias occurs within the Vine program, I suggest running this same analysis on all 50 datasets. That way, we can really delve into the numbers and more accurately determine if positiviy bias occurs within the Vine Program. </p>


