# Recommendations with IBM

### Table of Contents

1. [Installation](#installation)
2. [Libraries Used](#libraries)
3. [Project Motivation](#motivation)
4. [Data](#data)
5. [Project Outline](#projectoutline)
6. [Licensing, Authors, and Acknowledgements](#licensing)

### Installation <a name="installation"></a>

No installations needed. Used libraries available via Anaconda package manager.

### Libraries used: <a name="libraries"></a>
1. [Numpy](https://www.numpy.org/)
2. [Pandas](https://pandas.pydata.org/)


### Project Motivation <a name="motivation"></a>
This project provided an opportunity to get exposure to the generation of recommenders.
Involves the expansion of the understanding of Rank based filtering, Collaborative filtering, and SVD models for recommendations.


### Project Data <a name="data"></a>
Provided by IBM in collaboration with Udacity.

### Project Outline <a name="projectoutline"></a>
There are three components in this project.

1. Exploratory Data Analysis

	- Getting to know the data and developing data understanding.
	- What is the distribution of how many articles a user interacts with in the dataset?
	- The number of unique articles that have an interaction with a user.
	- The number of unique articles in the dataset (whether they have any interactions or not).
	- The number of unique users in the dataset. (excluding null values)
	- The number of user-article interactions in the dataset.

2. Rank Based Recommendations
	
	- Find the most popular articles simply based on the most interactions. 
    - In the absence of ratings for any of the articles, assume the articles with the most interactions are the most popular. 
    - These are then the articles we might recommend to new users (or anyone depending on what we know about them).

3. User-User Based Collaborative Filtering

	- In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.
  
4. Matrix Factorization

	- Using the user-item interactions, build out a matrix decomposition. Using decomposition, evaluate performance.

### Licensing, Authors, and Acknowledgements <a name="licensing"></a>

* [Udacity](https://www.udacity.com/)