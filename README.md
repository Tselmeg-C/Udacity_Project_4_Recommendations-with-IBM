# Udacity_Project_4_Recommendations-with-IBM

Introduction

For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and made recommendations to them about new articles I think they will like. Below is an example of what the dashboard could look like displaying articles on the IBM Watson Platform.
![alt text](https://github.com/Tselmeg-C/Udacity_Project_4_Recommendations-with-IBM/blob/master/screen-shot-2018-09-17-at-3.40.30-pm.png)
Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

My project is devided into the following tasks

I. Exploratory Data Analysis

Before making recommendations of any kind, I explored the data I am working with for the project. Dive in to see what I can find. There are some basic, required questions to be answered about the data provied from the project designer. 

II. Rank Based Recommendations

To get started in building recommendations, I first found the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using NLP skills, one can come up with some extremely creative ways to develop a content based recommendation system. 

V. Matrix Factorization

Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using decomposition, I got an idea of how well I can predict new articles an individual might interact with (spoiler alert - it isn't great). I finally discuss which methods you might use moving forward, and how I might test how well my recommendations are working for engaging users.
