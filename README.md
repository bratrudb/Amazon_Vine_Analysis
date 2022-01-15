# Amazon_Vine_Analysis

## Overview of the Analysis
The purpose of this analysis was to analyze reviews of books on Amazon using PySpark, PGAdmin, and AWS.

## Results
  - How many Vine reviews and non-Vine reviews were there?
    - My dataset had 399,745 non-Vine reviews after filtering out reviews with less than 20 votes and less than 50 percent helpful votes. My dataset did not include any Vine program reviews that met that criteria.
  - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - There were 241,836 5 star non-Vine reviews that meet the above criteria. There were no 5 star Vine reviews.
  - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    - 60.5 percent of non-Vine reviews were 5 stars.


## Summary
Because my dataset did not include any Vine program reviews, I cannot speak to the positivity bias for the reviews on the Vine program. To test if there is any positivity bias in a dataset that includes Vine program reviews, a two-sample t-Test could be run on the percentage of 5 star ratings for the Vine and non-Vine datasets to determine if there is a statistically significant difference in the number of 5 star reviews.
