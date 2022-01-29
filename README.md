# Amazon_Vine_Analysis

## 1.	Overview of the analysis:

The purpose of this Project is analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufactures and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

From over approximately 50 databases we choose the Video Games review and used PySpark to perform the ETL  process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Also to determine if there is any basis toward favorable reviews from Vine member in the dataset.

## 2.	Results: 

### Deliverable 1 
<img width="308" alt="customer_table" src="https://user-images.githubusercontent.com/37987602/151638916-446073c7-e35f-4a6b-bffa-c2b0ea054fb1.png">
<img width="723" alt="products_table" src="https://user-images.githubusercontent.com/37987602/151638926-076f565c-ae68-447c-9822-866a1172891e.png">
<img width="634" alt="review_table" src="https://user-images.githubusercontent.com/37987602/151638929-71d77835-3104-4c52-bfdf-860cd73ab21d.png">
<img width="652" alt="vine_table" src="https://user-images.githubusercontent.com/37987602/151638933-d436944a-13f8-4acb-9e51-eacb30b3da53.png">


- How many Vine reviews and non-Vine reviews were there?

![Vine_Reviews](https://user-images.githubusercontent.com/37987602/151638897-3096b8cf-04fc-4654-801d-e0b49590c659.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![5star_reviews](https://user-images.githubusercontent.com/37987602/151639081-c5443135-b779-42ad-a700-6ba399377c8a.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![Percentage_paid_reviews](https://user-images.githubusercontent.com/37987602/151639089-48e65c7e-78aa-449a-bfd2-288b00e0c81c.png)

## 3. Summary:

According to the results we can conclude that with the video games, there is no need to use the paid Vine program in order to get reviews. The total number of unpaid_vain reviews, is higher and also mora than 50% of unpaid reviews have a 5 star rating. 
