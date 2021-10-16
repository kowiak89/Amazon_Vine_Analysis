# Amazon_Vine_Analysis

## Objective:
The objective of this assignment was to analyze amazon review data to determine if there was any bias from paid vine reviewers.  The data set was collected from amazon and prepared using PySpark and SQL.

## Results:
From the analysis we obtained the following results:
* The total number of reviews for vine and non-vine reviewers
  * Vine Reviewers: 463
  * Non-Vine Reviewers: 25094
* The total number of 5 star reviews for vine and non-vine reviewers
  * 5 Star Vine Reviews: 202
  * 5 Star Non-Vine Reviews: 12033
* The percentage of 5 star reviews for vine and non-vine reviewers
  * Percent of 5 star Vine Reviews: 46.6%
  * Percent of 5 star Non-Vine Reviews: 48.0%

## Summary:
From the results we can clearly see that there is no positivity bias among vine reviewers given that their percentage of 5 star reviews is lower than the non paid reviewers.  If there was positivity bias we would have seen the percentage of 5 star reviews to be significantly higher than the non-vine reviewers.  While this analysis showed that there is no positivity bias for 5 star reviews it does not show the full picture.  Perhaps there is bias that can only be demonstrated if all star ratings levels are analyzed.  A future analysis that scored all rating levels would be more predictive of any positivity bias for the paid vine reviewers.
