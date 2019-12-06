# ShakespeareCharacterClassification
Using this dataset (https://www.kaggle.com/kingburrito666/shakespeare-plays/data), engineer a few features and classification models to determine the actor speaking based on other information available.

I decided to try out a few different classification models to see how each performed.

## TL;DR
Clean null values ->
One-hot encode play names ->
Vectorize words (mono-grams) ->
K-nearest neighbors (very bad, 7%) ->
Decision tree (ok, 70%) ->
SVM (very bad, 5%)
