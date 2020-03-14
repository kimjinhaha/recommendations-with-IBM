# recommendations-with-IBM
Recommendation engine with Watson Studio data from IBM, a part of Data Science Nanodegree by Udacity.

## Introduction
In this project, interactions that users have with articles on the IBM Watson Studio platform are anlayzed to make recommendations to users.

### The Jupyter Notebook includes the following steps

1. Exploratory Data Analysis
Before making recommendations of any kind, I explore the data I am working with for the project. 

2. Rank Based Recommendations
To get started in building recommendations, I first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles I might recommend to new users (or anyone depending on what we know about them).

3. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, I could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

4. Matrix Factorization
Finally, I complete a machine learning approach to building recommendations. Using the user-item interactions, I build out a matrix decomposition. Using the decomposition, I get an idea of how well I can predict new articles an individual might interact with. I discuss which methods I might use moving forward, and how I might test how well my recommendations are working for engaging users.
