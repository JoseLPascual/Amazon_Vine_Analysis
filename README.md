# Amazon_Vine_Analysis

## Overview

I was tasked by Jennifer with analyzing Amazon reviews written by members of the paid Amazon Vine program to analyze whether there exists bias toward favorable reviews from Vine members in my chosen dataset.  The dataset chosen is that of German Amazon reviews, as I have a specialization in the Germanophone market.

## Resources

- Data Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_multilingual_DE_v1_00.tsv.gz
- Software: PySpark 3.1.2 via Google Colab, pgAdmin 4 Version 5.2

## Results

After executing the required code, the following results were obtained:

- Total number of reviews: 52,100
- Total number of paid reviews: 26
- Total number of unpaid reviews: 29,264
- Total number of 5-star reviews: 438,977
- Total number of paid 5-star reviews: 9
- Total number of unpaid 5-star reviews: 15,784
- Total percentage of paid 5-star reviews: 34.6%
- Total percentage of unpaid 5-star reviews: 53.9%

## Summary

At least as it concerns German Amazon reviews, there does not exist a positivity bias in favor of Amazon Vine reviews (34.6% of all paid reviews receiving a five-star rating, compared to 53.9% of all unpaid reviews receiving said rating,) but it may be so because of the low number of paid reviews (26 paid reviews versus 29,264 unpaid reviews.)  The only additional analysis that I would recommend would be for there to be more paid Amazon Vine reviews concerning this particular demographic to then be able to generate a more agreeable sample size.
