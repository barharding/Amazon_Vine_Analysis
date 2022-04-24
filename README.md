# Amazon_Vine_Analysis

## Overview of the analysis

Explain the purpose of this analysis.

This analysis was performed using Pyspark on Google CoLab, RDS on AWS, PGAdmin, as well as data retrieval from AWS S3 storage for the purposes of analyzing product review data by Amazong Vine members and non-Vine members.  The Electronics product segment was selected for this analysis from a list of 50.

## Results

The following questions are answered using the results shown in the final_df dataframe shown in **_Figure 1_** below.

1. How many Vine reviews and non-Vine reviews were there?  There were 50,753 reviews
2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?  There were 454 Vine 5-Star reviews and 23,043 non-Vine 5-Star reviews
4. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?  Vine - 42% and non-Vine 46%

**_Figure 1: Summary Results_**
![Final_df](images/D2_Q5.png)


## Summary 

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.



