# Toxic-Comment-Classification

## Data Description
You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behaviour.
The types of toxicity are:
* toxic
* severe_toxic
* obscene
* threat
* insult
* identity_hate

## File Descriptions
* train.csv: The training set, contains comments with their binary labels
* test.csv: the test set, predict toxicity probabilities for these comments

> Note
* Here, I have used GloVe word embedding for encoding.
* Model.h5 file is of 47 MB and can be generated via code