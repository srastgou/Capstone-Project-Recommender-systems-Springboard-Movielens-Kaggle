 

## Movie Recommender System 


### Overview
Nowadays, we need recommender systems almost everywhere in our lives. Therefore, retailers are become more interested in recommender systems to analyze patterns of user interest in products and provide personalized recommendations. The first goal of this project is understanding, analyzing, and correlating the trend in average rating movies of different genres. The second goal is building recommender engines to provide recommendations to different users and build different machine learning models to predict the rating of each movie.
Business Objective
The recommender system is useful to any business that makes money via recommendations. Since we want to work with movie dataset, the client of this project could be Amazon, Netflix, Hulu, HBO, etc.
Giving good recommendations will help users spend less time searching for their type of movie and having a recommender platform. This will help the customer to continue with the service and having a good experience.

### Data
I will use two datasets for this project as:

 The first dataset is collected from a free, noncommercial movie recommender as  MoviLens.org. (https://grouplens.org/datasets/movielens).
 This recommender is like Netflix, minus the ability to watch movies. The dataset which was released in April 2015 contains 20 million ratings and 465,000 tag applications applied to 27,000 movies by 138,000 users (movies.csv, ratings.csv, link.csv). The data has been created in October 2016. Users were selected at random for inclusion. All selected users had rated at least 20 movies.
 
The second dataset is collected from (https://www.kaggle.com/karrrimba/movie-metadatacsv). We have more features in this dataset like information about revenue, budget, release date, popularity,... .
 

### Solution

How to get the insight about how people’s rating change for different genres over the years?

Getting different distributions of the movie-ratings and movie-relevancy across title, genre, year, and tag of each movie can give the insight about how people’s taste vary over the years. Different inferential statistics and visualization techniques can be implemented to deliver a better understanding of the trends.

How to recommend movies?

In this work different Collaborative filtering (CF)  and Content-base filtering techniques will be used to analyze relationships between users and interdependencies among products to identify new user-item associations. Most CF algorithms are based on a user-item rating matrix where each row represents a user, each column an item. The entries of this matrix are ratings given by users to items. One of the primary areas of collaborative filtering is the latent factor models which are based on matrix factorization (Singular value decomposition (SVD)). Ratings.
How to predict movie ratings?
In this work different different machine learning techniques like Random Forest, Support Vector Machine, K-Nearest Neighbors,... will be implemented to predict the rating of the testset.

### Workflow
- Collecting data and applying data wrangling methods
- Starting exploratory data analysis to find trends
- Story telling
- Conduct further data analysis to identify relationships between different variables
- Perform in-depth analysis using collaborative filtering and machine learning techniques to recommend and  predict

### Deliverables
- Final report
- Jupyter notebook .ipynb code
- Slide deck
- Presenting the project

