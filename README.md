# Amazon-Product-Recommender-System-by Sakshi Sakshi 
Performed sentiment analysis on Amazon Review Dataset available at http://snap.stanford.edu/data/web-Amazon.html

Online shopping is all over the internet. All our needs are just a click away. The biggest online shopping website is Amazon. Amazon is known not only for its variety of products but also for its strong recommendation system.     

In our project we are taking into consideration the amazon review dataset for Clothes, shoes and jewelleries and Beauty products. We are considering the reviews and ratings given by the user to different products as well as his/her reviews about his/her experience with the product(s).     

Based on these input factors, sentiment analysis is performed on predicting the helpfulness of the reviews. 
Moreover, we also designed item-based collaborative filtering model based on k-Nearest Neighbors to find the 2 most similar items.     

### Convert json to CSV using following commands
```
dataframe = pd.read_json('reviews.json')
dataframe.to_csv('reviews.csv', sep=',', index=False)
```
### Algorithms performed
#### Sentiment analysis:    
1. [Logistic Regression]   
2. [Naive Bayes]    
3. [LSTM]
    
    
### References:    
1. [J. McAuley and J. Leskovec. Hidden factors and hidden topics: understanding rating dimensions with review text. RecSys, 2013.](http://i.stanford.edu/~julian/pdfs/recsys13.pdf)    
2. http://jmcauley.ucsd.edu/data/amazon/    
3. https://www.kaggle.com/snap/amazon-fine-food-reviews   
