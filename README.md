# Temporal Drift of User Ratings on Movie Recommender Systems

## Why Pseudo Name 'Project Alpha' ? 

I like to keep it simple and since this one my first project I used 'alpha' probably next project will be 'beta'.

## What do I mean by 'Temporal Drift Effect of User Ratings' ?

The slow change of users' old ratings with the effect of time.

## What is it about ?

When designing collaborative filtering based recommendation systems, the selection of best neighbors in similarity measure is a key challenge. 

By examining the temporal drift effects of the movie ratings on the selection of best neighbors, the performance of the movie recommender system is aimed to be tested and if possible find algorithms to increase its accuracy by using the temporal drift effect.

The main intuition is that "The Newer the Better" for the numerical effect of the movie rating dates of each user. 

## Scope of the project

One of the well known method of Collaborative Filtering is known as Nearest Neighborhood algorithm. 

To select best neighbors, there are several similarity measures which are grouped as correlation based similarity(like Pearson Correlation, Spearman, Kendallns τ correlation), vector cosine based similarity, and conditional probability based similarity measures.

We will be using these similarity measures along with MovieLens or the Netflix Price dataset.

In this project, while examining the temporal drift effect, we wil not be designing a full-fledged application but rather a test environment which we can compare miscellaneous metrics. Test environment and all related algorithmic design will be coded in python.
The test environment will offer different similarity measures as well as accuracy metrics which will show the effect of temporal drift on user ratings by providing appropriate plots.

By the help of test environment, if we achieve finding tangible temporal drift effect, we will try to develop a temporal drift based algorithm for selecting best neighbors in collaborative filtering based recommendation systems.

## Goals of the project

All in all, the following question is to be answered: 

* Is the proposed temporal drift-based algorithm better or worse than the standard approach.

The related accuracy metrics will be not only the very well-known metrics ( such as confusion matrix, ROC curve, coverage, serendipity, diversity ), but also the new improved metrics selected from different journals as informedness, markedness, Matthews correlation.
