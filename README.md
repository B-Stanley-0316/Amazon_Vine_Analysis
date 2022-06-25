# Amazon Vine Analysis

## Overview of Analysis

Analyze Amazon reviews written by members of the paid Amazon Vine program. In this analysis, you will find if there are any bias towards favorable reviews from Vine members in the dataset chosen and displayed in the DataFrames below.


### DataFrames Created and Used

#### Paid Vine Reviews DataFrame

![Paid_Vine_DF](Resources/Paid_Vine_DF.png)

#### Unpaid Reviews DataFrame

![Unpaid_Vine_DF](Resources/Unpaid_Vine_DF.png)


## Results

### Total Number of Reviews

* Number of Vine Reviews

![Total_Paid](Resources/Total_Paid_Reviews.png) 

* Number of Non-Vine Reviews

![Total_Unpaid](Resources/Total_Unpaid_Reviews.png)




### Total Number of 5-Star Reviews

* Number of 5 Star Vine Reviews

![Paid_5Star](Resources/Paid_5Star_Reviews.png) 

* Number of 5 Star Non-Vine Reviews

![Unpaid_5Star](Resources/Unpaid_5Star_Reviews.png)




### Percentage of 5-Star Reviews

* Percentage of Vine Reviews - 5-Star Ratings

![Paid_5Star_Percentage](Resources/Paid_5Star_Reviews_Percentage.png)

* Percentage of Non-Vine Reviews - 5-Star Ratings

![Unpaid_5Star_Percentage](Resources/Unpaid_5Star_Reviews_Percentage.png)



## Summary

As shown above, 66.6% of the reviews in the Vine program were 5-star reviews, whereas 56.5% of non-Vine reviews were 5-star reviews. Although there is not a huge difference in the percentages in this dataset, it still shows there is some bias in the 5-star reviews. The vine reviews in this dataset were very low, 6-9 reviews shown against the almost 40,000 regular reviews, this may not paint a perfect picture about the bias towards reviews.

A further analysis that could be performed is pulling the lower starred reviews (1-2 stars) and find if those are also paid or unpaid to see a more complete picture of if there is more or less bias on the Vine reviews.
