# Native Bayes Classification from Scratch

This repository provides a **from-scratch implementation of the Naive Bayes classifier** for binary classification. It demonstrates how the algorithm works internally, including probability estimation, likelihood computation, and class prediction using Bayes’ theorem.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Algorithm Overview](#algorithm-overview)  
- [Results](#results)

## About

The **Naive Bayes classifier** is a probabilistic machine learning model commonly used for classification tasks. It estimates the probability of each class based on Bayes’ theorem and assumes feature independence.

This project implements Naive Bayes manually (without scikit-learn’s built-in classifier), providing insight into calculation of prior probabilities, likelihoods, and prediction logic.

## Features

- From-scratch implementation of **Multinomial Naive Bayes**
- Laplace smoothing (alpha parameter)
- Log-probability computation for numerical stability
- Support for:
  - **Unigram** representation
  - **Bigram** representation
  - **TF-IDF** vectorization
- Experiments with and without **stopword removal**
 
## Algorithm Overview

1. **Prior Estimation**  
   Estimate the prior probability of each class from the training data.
2. **Likelihood Calculation**  
   Compute feature likelihoods given each class (using distribution assumptions or frequency counts).
3. **Prediction**  
   Use Bayes’ theorem to compute posterior probabilities for each class and choose the class with the highest posterior.

This implementation supports continuous and categorical features.

## Results

<img width="695" height="667" alt="image" src="https://github.com/user-attachments/assets/9f743052-921a-437f-aa94-36ad46b60d38" />


```bash
git clone https://github.com/meddyahya/Native-Bayes-Implementation---Classification.git
cd Native-Bayes-Implementation---Classification
pip install -r requirements.txt
```

