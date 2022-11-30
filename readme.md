## Dataset Amazon customer product reviews

Based on the Amazon customer product review datasets which are available at: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt 

This site contains a number of large review datasets made available by Amazon and broken down by product category. We will sample a number of these, taking into account the need to keep the sample representative of the larger datasets. This will be done by using the 'star_rating', 'vine' and 'verified_purchase' features to proportionally reduce the dataset for performance reasons. 

The dataset was chosen for its richness of features, the flexibility of classification that they will present and for the opportunity to run some sentiment analysis on the reviews. The main challenge will be in drawing meaningful conclusions from the reduced dataset.   

We'd be interested in investigating topics like the following:

- Are there anomalous patterns (perhaps indicating fake reviews) ?  
- Do sentiments change across product groups? Are people more likely to complain about certain product groups? Can we see a decline in customer satisfaction over time on certain products?
- Do people find certain types of reviews helpful? What is it about the review that might make it helpful?
- Do paid for reviews impact the review itself (feature 'vine' in the dataset) and is it possible to predict whether the review is by a Vine program member based on the review text?
- Impact of verified/non verified status on the review helpfulness and in turn how it affects the product sentiment 