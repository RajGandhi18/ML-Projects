# Fake News Detection
The objective of this project is to classify the news as real or fake.

## Table of Contents
* [Methods Used](#methods-used)
* [Technologies](#technologies)
* [Project Description](#project-description)

## Methods Used
 * Lemmatizing
 * Name Entity Recognition
 * Topic Modelling
 * Word2Vec Model
 * Data Visualization
 * Predictive Modelling

## Technologies
* Python
* Jupyter

## Project Description
The dataset used to build this project contains about 6K text data. The csv file contains title of the news, the news description and the label for that respective news.
For understanding the data better wordclouds, Name Entity recognition and topic modelling are used. Before building the classifier we have to convert the words to numerical values,
for this word2vec is used so that the semantic meaning of the word is taken into account. For building the model lightgbm is used and for hyperparamterer tuning optuna is used.
