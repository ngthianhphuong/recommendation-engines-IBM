# recommendation-engines-IBM
Algorithm that recommends the most relevant articles to [IBM Watson Studio platform](https://dataplatform.cloud.ibm.com/) users.

## Installation

This project requires Python and usual libraries used in data science such as:
- numpy
- pandas
- matplotlib

To easily check the code at the same time as the output, it is recommended to install Anaconda and Jupyter Notebook.

## Dataset Description

Two datasets are available:

- user-item-interactions.csv records user id and article id that have been interacted to each other. 
- articles_community.csv provides more details about the articles.

## Project Motivation

On IBM Watson Studio Platform, users read articles shared in data science and artificial intelligence community. The interactions that users have with articles are recorded (no rating was available).
![Screenshot](screen-shot-IBM.png)
 
While the above dashboard shows only newest articles, it will be more relevant to recommend the most pertinent articles to users.

## Task Description

The main tasks in this project are the following:

#### Exploratory Data Analysis
Explore the number of users, articles and interactions available in the dataset as well as main statistic metrics.

#### Rank Based Recommendations
Build functions that output the top k most popular articles.

#### User-User Based Collaborative Filtering
Build functions that find the most similar users based on interactions in the past and make recommendations to a specific user with articles seen by its most similar users.

#### Matrix Factorization
Machine learning approach to building recommendations. Using Singular Value Decomposition to predict interaction between users and articles, then make recommendations. Discussion about methods that should work well in practice.

## Licensing, Authors, Acknowledgements
The dataset was provided by Udacity as part of its [Data Scientist Nanodegree program](https://www.udacity.com/course/data-scientist-nanodegree--nd025). Dataset credit belongs to [IBM Watson Studio](https://dataplatform.cloud.ibm.com/).