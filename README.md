### Recommendation system - Foodpanda case study:

Foodpanda front end (www.foodpanda.sg) is displaying by restaurant level. Each of restaurant has unique primary cuisine and multiple secondary cuisines. The platform wants to create a recommendation lane to customers top 3 cuisines they are likelihood to choose but have never ordered before. 

Question: 
1. Please advise at least one model for recommending top 3 cuisines which customers are likelihood to choose but have never ordered before. Briefly describe how this recommendation model works
2. Giving below is a dataset of 100 customers with orders from different cuisines. Please use Python/Excel or any application to execuse your recommended model above to give results.

In this notebook, we attempt to use foodpanda order history of a 100 users to create a recommendation system. The approach attempted is User-based Collaborative Filtering (read more: https://www.geeksforgeeks.org/user-based-collaborative-filtering/). Essentially we are attempting to find other users that are identical/similar to any given user to understand the user's preference.
