# Amazon Vine Analysis

## Overview
The Amazon Vine Analysis used the cloud ETL process to access approximately 50 datasets of video games reviews from Amazon. Using the data acquired from the reviews, a bias can then be determined. PySpark was used for the ETL process to extract the dataset, transform the data, and load it into their respective tables in pgAdmin and calculate different metrics. 

## Results:
1.  How many Vine reviews and non-Vine reviews were there? The total number of vine reviews were 94 and the total number of non-vine reviews were 40,471. 
2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? The total number of vine reviews that were 5 stars were 48 and the total number of non-vine reviews the were 5 stars were 15,663. 
3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? The percentage of vine views that were 5 stars was 51% and the total percentage of non-vine reviews that were 5 stars was 38%. 

## Summary
When looking at the percentages, the total number of vine reviews that were 5 stars were 51%, while the non-vine were 38%. This would indicate a positive bias for reviews in the Vine program. For further analysis it would be good to apply a NLP sentiment analysis to check for the words used in the vine reviews vs the non-vine reviews.
