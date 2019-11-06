# MovieRecommendation

This project is a part of the Personalization course at Columbia University.

#### Project Status: [Completed]

## Project Objective
The purpose of this project is build a recommendation system for a digital media company. The recommendation system is designed to build customized movie recommendations for users which can improve user experience, attract new users and retain current users. In this case, the digital media company can be more professional and popular.

### Methods Used
* Exploratory Data Analysis
* Data Visualization
* Item/User Based Collaborative Filtering
* Model Based Collaborative Filtering
* Matrix Factorization
* KNN (K nearest neighbors)
* Hyper-parameter Tuning

### Technologies
* Python
* Pandas, Numpy, jupyter
* PySpark
* Surprise

## Project Description
The goal of this project is to build up a recommendation system using various collaborative filtering models to recommend movies to users that they might like. In this project, we have investigated three different recommendation models in order to select the ones that will make accurate and reasonable suggestions to the users. 

They are baseline model, Item/User based collaborative filtering, and Model based collaborative filering. The baseline model acts as a baseline that simply uses user and item biases to make predctions. The User based CF utilizes the similarity metrics to find the closest neighbors of a particular user and uses the neighbors to predict the ratings of the movies that the use hasn't viewed yet. Finally, the Model based collaborative filtering is trying to transform the ratings into a matrix that sets users as index and movies as columns. By solving the matrix factorization problem, the model has the power of approximateing the ratings of any movies for a given user. 

After setting up the three models, we need to optimize the hyper-parameters in each model and compare the best of the three models. In order to evaluate the performance of different models, we test the predictions in basically two dimensions, accuracy and coverage. Per model with the optimized hyper-parameters, we are able to leverage it to make personalized movie predictions for any users. 

## Needs of this project

- data sampling
- data exploration/descriptive statistics
- recommendation modeling
- write-up/reporting

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data could be extracted from [here](https://grouplens.org/datasets/movielens/).

    *Please use the “20Ml” data set for education and development (20M ratings; 190 MB)*
    
3. Movie recommendation could be found [here](https://github.com/nding17/MovieRecommendation).
4. Write-up/report could also be found [here](https://github.com/nding17/MovieRecommendation).

## Featured ALL-IN-ONE Notebook
* [movie recommendation.ipynb](https://github.com/nding17/MovieRecommendation/blob/master/movie%20recommendation%20v8.ipynb)


## Contributing Members

|Name     |  Email   | 
|------|-----------------|
|[Naili Ding](https://github.com/nding17)| nd2588@columbia.edu        |
|[Tao Li](https://github.com/Megatao) |     tl2863@columbia.edu    |
|Chaoyue Zheng |     cz2529@columbia.edu    |
|Jinglin Chen |     jc5059@columbia.edu    |


## Contact
* Feel free to contact any of our team members with any questions or if you are interested in contributing!
