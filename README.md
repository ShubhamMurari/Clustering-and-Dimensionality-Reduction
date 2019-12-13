# Clustering-and-Dimensionality-Reduction
In this project I experimented with K-Means Clustering and Expectation Maximization clustering, tried my hands with various Feature Dimensionality Reduction techniques like - Forward Selection, PCA, ICA and Randomized Projection

## Problem Summary:

We are working two different Classification Problems here ‘Appliances Energy’ and ‘Bank Marketing Data’. There are 19735 and 45211 instances (records) respectively with no missing values. The energy data was logged on a time basis where the Temperature and Humidity Conditions of a house were monitored with the help of sensors, we are classifying between high and low energy consumptions.

On the other hand, in bank marketing data we are classifying between whether a customer is making a term deposit or not based upon the demographic details and historic data which is available to us.

## Goal:

The main goal for this assignment is to implement various clustering algorithms taught during the lecture followed by Dimensionality Reduction (PCA, ICA, Randomized Projections and Forward Selection) and again run the clustering. Analyze the results by comparing it with current and previous NN outputs.

## Experiments:

I experimented with k-value (for K-means clustering), principal components and other clustering tasks that were mentioned in the assignment doc.

## Exploratory Analysis and Feature Engineering:
I followed the usual process of Exploratory Data Analysis for this assignment, which I did last time just to evenly compare the results.
After successful implementation of the following algorithms in the order which was given in the assignment i.e.

## Clustering Algorithms:
### 1. K-means Clustering
### 2. Expectation Maximization

## Feature Dimensionality Reduction Algorithms:
### 1. Forward Selection (using Logistic Regression in the Feedback Loop)
### 2. PCA – Principal Component Analysis
### 3. ICA – Independent Component Analysis
### 4. Randomized Projections

I used Python (Jupyter Notebook) for the coding and implementation of various algorithms. Instructions are duly mentioned in the README.txt file to execute the code successfully.

The 5 major tasks for this exercise, which I am going to describe below with the help of various plots are-
### 1. Run the clustering algorithms on your datasets and describe the observations (with plots).
### 2. Apply the dimensionality reduction algorithms on datasets and describe the observations (with plots).
### 3. Run the clustering algorithms again, this time after applying dimensionality reduction. Describe the difference compared to previous experimentation (with plots).
### 4. Run your neural network learner from assignment 3 on the data after dimensionality reduction (from task 2). Explain and plot the observations (error rates, etc.)
### 5. Use the clustering results from task 1 as the new features and apply neural network learner on this new data consisting of only clustering results as features and class label as the output. Again, plot and explain the results.
