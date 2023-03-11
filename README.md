# Movie Recommendations: Non-convex optimization with sparse matrices

This is a project exploring some basic algorithms to try and recover sparse matrices in order to make prediction on how users would rate movies.
Included in the repository is a dataset(mat_comp_small) sourced and modified from [dataset](https://grouplens.org/datasets/movielens/). Below describe the input.

Input. The input has two parts: 
(1) the training data, consisting of k ratings across m movies and n users, and 
(2) the q queries for which your algorithm needs to provide predictions.
You are given an input file mat comp. The first line of this file contains three integers n, m, k. 
This is followed by k lines, where each line contains three numbers i, j, and Mi,j, specifying user i’s rating for movie j. 
The ratings are made on a 5-star scale with half-star increments (0.5 ≤ Mi,j ≤ 5.0). On the next line, the input file specifies an integer q. 
This is followed by q lines, where each line contains two integers i, j, asking you to predict how user i will rate movie j.

The notebook contains the code used for data cleaning, model training, and predictions. Some algorithms are alternating minimization and gradient descent.
