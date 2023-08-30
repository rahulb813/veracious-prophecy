# Veracious Prophecy
## Introduction
- A logistic regression based ML model that's trained with a dataset with 20k+ values.
- Predicts real v/s fake news based on text stemming.
## Intuition
The use of logistic regression is done because the final output predicted by this model 
is supposed to be a binary value which results that the news/article is real or fake.
Refer [here](https://www.geeksforgeeks.org/understanding-logistic-regression/) for further details.

## Technologies Used
- Python
- sklearn
- numpy
- PorterStemmer

## Dataset
A single [`train.csv`](https://www.kaggle.com/c/fake-news/data) dataset obtained from [Kaggle](https://wwww.kaggle.com) is split into 80%-20%
for training and testing the model.
