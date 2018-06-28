# Yelp review sentiment analysis
Project analysis sentiment associated with reviews of restaurant on Yelp.


## About

In this post, we will be training a LSTM (Long-Short-Term-Network), which is a type of RNN to classify text data from Yelp reviews. During this project, Goal of this project is to show how to Train a LSTM, and how to Tune the model to reduce variance and obtain higher accuracy on Validation data.


## Approach

Took the following approach to achieve our goal :

* Preparing the data for learning
* Defining the model and training it
* Tuning the model and removing variance

## Data

Used *Yelp Dataset*. It contains user reviews for millions of local businesses, along with a star rating that user gave the business. As an example, here are a few examples from the data:

> “A-M-A-ZING!!!!!!!!!!!!!! LOVE THIS PLACE!!!!!!! Everything on the menu looked so good!! Garlic chicken was the BOMB!!!!!! MUST EAT AT THIS PLACE!!! I recommend ordering ahead before you go! Gets very busy!!!” — 5 Stars.

`.`

> “burgers are very big portions here. definitely order the onion ring tower to share…Milkshakes are tasty! My personal favourite — the vanilla one.” — 3 Stars.

`.`

> “Food is very bland — not authentic at all. meant to cater to the customers who have never eaten Vietnamese food before. Definitely will not be returning!” — 1 Stars

To download the dataset you can [visit here](https://www.yelp.com/dataset/challenge).

## Data Preparation

The first part of the project is to prepare the data. As we saw in the examples above, the reviews are very distinct. Some of them have symbols, have weird punctuation symbols, and some even have non-alphanumeric characters. We will clean these and keep the most relevant strings and words from the reviews.

Detailed process is provided in the notebook [here](/notebook)
