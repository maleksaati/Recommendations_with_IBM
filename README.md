#  Recommendations With IBM 

#### Introduction

For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

#### Overview

###### [](https://github.com/prateeksawhney97/Recommendations-With-IBM-Project#i-exploratory-data-analysis)I. Exploratory Data Analysis

Before making recommendations of any kind, we will need to explore the data we are working with for the project. 

###### [](https://github.com/prateeksawhney97/Recommendations-With-IBM-Project#ii-rank-based-recommendations)II. Rank Based Recommendations

To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

###### [](https://github.com/prateeksawhney97/Recommendations-With-IBM-Project#iii-user-user-based-collaborative-filtering)III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

###### [](https://github.com/prateeksawhney97/Recommendations-With-IBM-Project#v-matrix-factorization)V. Matrix Factorization

Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using the decomposition, we will get an idea of how well we can predict new articles an individual might interact with. We will finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.