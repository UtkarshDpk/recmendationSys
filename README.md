# Recommender Systems
Recommender systems try to capture patterns and similar behaviors, to help predict customer selection choices. 
Recommender systems have many applications usually at play on many websites. For example, suggesting books on Amazon and
movies on Netflix.

In this project we look at two different types of Recommender Systems:
1. Content-based and,
2. Collaborative filtering

The main difference between them can be summed up by the type of statement that a consumer might make. For instance, the main paradigm of a Content-based
recommendation system is driven by the statement: “Show me more of the same of what I've liked before." Content-based systems try to figure out what
a user's favorite aspects of an item are, and then make recommendations on items that share those aspects.
Collaborative filtering is based on a user saying, “Tell me what's popular among my neighbors because I might like it too.” 
Collaborative filtering techniques find similar groups of users, and provide recommendations based on similar tastes within that group.
In short, it assumes that a user might be interested in what similar users are interested in. 

Then there are Hybrid recommender systems (out of scope), which combine various mechanisms. In terms of implementing recommender systems, there are 2 types: Memory-based and Model-based.
In memory-based approaches, we use the entire user-item dataset to generate a recommendation system. It uses statistical techniques to approximate
users or items. Examples of these techniques include: Pearson Correlation, Cosine Similarity and Euclidean Distance, among others.
In model-based approaches, a model of users is developed in an attempt to learn their preferences. Models can be created using Machine Learning
techniques like regression, clustering, classification, and so on.
