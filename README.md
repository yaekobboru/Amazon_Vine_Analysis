# Overview of the analysis

  This analysis focus on analyzing Amazon reviews written by members of the paid Amazon Vine program.
  The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 
  Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. 
  PySpark used as an ETL tool to process data from AWS RDS instance to PgAdmin.google colab also used to make calculations.

# Results

  * There were 82 vine reviews and 24,742 non-vine reviews. 
  * The count of 5 stars vine reviews were 33 (40.24%).
  * The count of 5 stars non-vine reviews were 12807 (51.76%). 

# Summary
  
  There is a significant difference between the number of vine and non-vine reviews. This makes the non-vine reviews to be the dominant factor for the
  decision. additionally summing the totals of both and checking the gross percentage gives 51.72% which is almost the figure for non-vine reviews.
  So, based on this fact for SellBy there is almost a 50-50 bias for both reviews. 