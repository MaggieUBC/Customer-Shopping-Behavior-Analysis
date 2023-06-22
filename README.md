# customer_shopping_behavior_analysis
## Summary
-- This project used a dataset that published at Kaggle. https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset 

2. The given dataset is all about customer purchase transaction records, including visitorid, itemid, timestamps of view, add to cart, transaction.

3. Based on this dataset, I built a regression model to predict the purchase possibility of the online shopping customers and a recommendation model using both collaborative filtering and content based filtering method. 

4. For a recommendation system, this model simply build a function that based on product similarity and searching for products that purchased by people showing similar shopping behavior.

5. For the regression model, the first difficulty is how to obtain customer shopping behavior data from the transaction records. This notebook takes you from data cleaning, explortory data analysis, feature selection, feature evaluation, model selection, setting up machine learning pipeline, to model evaluation and interpretation. 

6. This final model is XGBoost Regressor with the R2 of 0.9936.

7. You may find how important exploratory data analysis and feature selection are through this project. To build an effective model, the first thing is to understand the data itself. 

8. Based on this ml model, it was found that maintaining regular and return customer is important in keeping or even increasing the value of their orders.

9. Neural network is also tried, but it does not obtain a better result than XGBoost as the size of data for a dl model is not enough. 
