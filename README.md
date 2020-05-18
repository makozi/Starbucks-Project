# Starbucks-Project

## Overview

Starbucks Udacity Data Scientist Nanodegree Capstone Project data set is a simulation of customer behavior on the Starbucks rewards mobile application. Starbucks sends offers to users that may be an advertisement, discount, or buy one get one free . 

### Data

This is the link to the [dataset](https://github.com/makozi/Starbucks-Project/tree/master/data)

This data set contains three files:

* The first file describes the characteristics of each offer, including its duration and the amount a customer needs to spend to complete it (difficulty).

* The second file contains customer demographic data including their age, gender, income, and when they created an account on the Starbucks rewards mobile application.

* The third file describes customer purchases and when they received, viewed, and completed an offer. An offer is only successful when a customer both views an offer and meets or exceeds its difficulty within the offer's duration.

## Statement of Problem

The problem is to build a model that predicts whether a customer will respond to an offer. The strategy for solving this problem has four steps. 

* Combining the offer portfolio, customer profile, and transaction data. Each row of this combined dataset will describe an offer's attributes, customer demographic data, and whether the offer was successful. 

* Assessing the [accuracy](https://developers.google.com/machine-learning/crash-course/classification/accuracy) and [F1-score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html) of a naive model that assumes all offers were successful. This provides a baseline for evaluating the performance of models that I construct. Accuracy measures how well a model correctly predicts whether an offer is successful. However, if the percentage of successful or unsuccessful offers is very low. For this situation, evaluating a models' [precision and recall](https://towardsdatascience.com/beyond-accuracy-precision-and-recall-3da06bea9f6c) provides better insight to its performance. I chose the F1-score metric because it is "[a weighted average of the precision and recall metrics"](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html). 

* Comparing the performance of [logistic regression](https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc), [random forest](https://towardsdatascience.com/the-random-forest-algorithm-d457d499ffcd), and [gradient boosting](https://machinelearningmastery.com/gentle-introduction-gradient-boosting-algorithm-machine-learning/) models. 

* Refining the parameters of the model that has the highest accuracy and F1-score.  

## Libraries

- Python Data Analysis Library
- Numpy
- Matplotlib
- Scikit-learn: Machine Learning in Python
- Seaborn: Statistical Data Visualization
- re: Regular expression operations
- os — Miscellaneous operating system interfaces
- Joblib: running Python functions as pipeline jobs

## Installation

Open this Jupyter Notebook on [Colab](https://colab.research.google.com/drive/1EhbBuojts4O6mfcR7leTQ8_jQKLl-HEP#scrollTo=LrLC6SIID2wy)

## License
This project is licensed under the [MIT License](https://github.com/makozi/Starbucks-Project/blob/master/LICENSE)

#### By: Marizu-Ibewiro Makozi