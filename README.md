# Amazon_Vine_Analysis
## Purpose
This analysis will inform as to whether there is a bias in the review process based on whether a customer is a vine member or not. some light analysis is performed on a video game review dataset pulled from the AWS service. The data is initially filtered to pull only records where the helpful_votes field accounts for 50% of the votes so we can be sure to pull mostly quality reviews.

## Results
- <h3>Total # of Reviews: </h3> 37,911 (only 90 Vine subscribers)</p>
- <h3>Total # of 5-star Reviews: </h3> 14,748 (44 Vine subscribers)</p>
- <h3>Percentage of 5-star Reviews: </h3> 49% for subscribers and 39% for non-subscribers</p>

## Conclusion
This is a difficult question to answer given that the non-subscriber dataset FAR outweighs subscribers. I performed an additional analysis where I pulled the unfiltered data (disregarding 50% helpful votes) and still did not get a very high number for subscribers. In my analysis I will say that subscribers are 44% - 49% likely to leave a 5-star review and non-subscribers are within the 31%-39% range for video game products. I would highly reccommend testing several other datasets, I believe there is correalation here but testing one dataset, especially one as niche as video games does not give me complete confidence, I would reccomend testing fashion or home products next. 
