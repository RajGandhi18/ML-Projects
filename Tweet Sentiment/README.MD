# Tweet Sentiment Analysis

>Categorize tweet into positive or negative.

>Python Libraries used for this project

>> nltk

>> sklearn

## Clean and Preprocess the tweet

> 1. Remove patterns 
>>> Remove patterns from the data such as words starting from "@".
> 2. Tokenize the tweet
>>> Convert the tweets into vectors of words.
> 3. Stemming the tweet
>>> Reduce the word to its word stem or to the roots of the words.

## Creating Wordcloud
> A data visualization technique indicating the most frequent words appearing in the positive and negative tweets.
## Extracting Features
> Extract the important features from the list of words using CountVectorizer
## Modeling
> Building a model using RandomForestClassifier.

> Using cross validation for evaluation of model

> Checking model performance using ROC Curve and confusion Matrix.
## Hyperparameter tuning
> Creating the dictionary of the params for hyperparameter tuning.

> Using Randomized Search Cross validation for finding the best parameters for our model.

> Checking the model performance using the new parameters.
