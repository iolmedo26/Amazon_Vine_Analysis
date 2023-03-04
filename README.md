# Amazon_Vine_Analysis

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project, we will study a dataset holding reviews for shoes by completing the following steps:

Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

Use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.
Write a summary of the analysis to submit to the SellBy stakeholders.

The vine program is based on detailed, honest and unbiased opinions. Our dataset showed that this is a valuable program because although some customers were paid to leave their reviews, the results did not show a higher percentage of 5-star ratings compared to non-paid reviewers.

This means that as a seller through the Amazon Vine program, you cannot buy 5-star reviews, which makes Amazon's review system trustworthy.


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
This is a very interesting result. The percentage of 5-star Vine reviews was 52% and the percentage of non-Vine 5-star reviews was 57%, meaning that from this specific dataset there was a higher percentage of reviewers that are not part of the vine program.


For that reason, our results mean that enrolling in a program that offers free products for reviews may not be the strategy that $ellby should focus on, instead they may consider focusing on the quality, durability and price of the products that will be part of the catalog. This will allow all consumers to leave a real opinion about these products.
