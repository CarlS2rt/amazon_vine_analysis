# Amazon Vine Analysis

## Project Overview

This project analyzes if there is any inherent bias in the Amazon Vine program. Since the Vine program pays members for reviews, this analysis attempts to determine if there is a statistically significant difference in the overall positivity of Vine reviews compared to non-Vine reviews. 

## Results for Vine and non-Vine Reviews

The initial analysis for this project focused on Vine reviews for digital video game downloads. For that product category, there were nearly 1700 reviews, but the analysis revealed that no reviews in that product category, meeting all other criteria, were Vine reviews. The results of that dataset are shown below:



![](https://raw.githubusercontent.com/CarlS2rt/amazon_vine_analysis/main/images/image-20220417140204745.png)

Since the initial data contained no Vine reviews to analyze inherent bias, another product category was chosen to complete the analysis. The final analysis focused on Amazon reviews for all video games, which most likely contains only physical copies of games. 

The final analysis of Amazon video game reviews yielded over 40,000 reviews all together. Of those reviews, only 94 were paid Vine reviews. The complete results of the analysis are below:

![](https://raw.githubusercontent.com/CarlS2rt/amazon_vine_analysis/main/images/image-20220417135848835.png)

The total percentage of 5-star reviews was 38.7%, and the percentage of 5-star unpaid reviews was the same. The overall 5-star percentage for Vine reviews was significantly higher at 51%.

## Summary

In sum, based on the results of the final dataset, there is clearly positivity bias in the Vine review program. The positivity bias for paid reviews in the sample was 12-13% higher than for the overall dataset and for the unpaid subset of reviews. From this, we can conclude that a positivity bias does exist as a result of Amazon paying reviewers. To further hone in on this, additional analysis should be performed on multiple datasets to determine if the positivity bias is statistically significant across all reviews or just reviews for video games. Additionally, across all datasets, it should be readily apparent if there is a consistent percentage of positivity bias in the Amazon Vine program. 
