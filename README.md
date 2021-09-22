# Amazon_Vine_Analysis

## Overview of Analysis

The purpose of this analysis was to analyze reviews written by members of Amazon Vine. In particular, this project analyzed the reviews of cameras bought by Amazon members. An ETL was performed by extracting the data from Amazon's repository and then loaded and analyzed in a notebook. I used Google Colab, Amazon RDS, and PgAdmin to analyze and record this data. The overarching goal was to determine the positivity rating on the cameras bought by these customers.

## Results:
- How many Vine reviews and non-Vine reviews were there?
  - There were 607 Vine reviews and 50522 non-Vine reviews.
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There were 257 Vine five star reviews and 25220 non-Vine five star reviews
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - 42.3 were Vine five star reviews and 49.9 non-Vine five star reviews

## Summary
There does not seem to be a bias between users of Vine and non-Vine customers when analyzing the reviews as a larger percentage the non-Vine reviewers were more likely to to give a five-star review for these cameras. Further analyses must be done before we can state this conclusively. A future analysis may want to analyze this data statistically by calculating a standard deviation and variance to see if the difference between the Vine and non-Vine customer reviews are statistically significant.
