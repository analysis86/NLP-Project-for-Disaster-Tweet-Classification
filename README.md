# Natural Language Processing with Disaster Tweet Classification

## Project Report:
https://github.com/analysis86/NLP-Project-for-Disaster-Tweet-Classification/tree/main/Note-Book

## Overview:
In this project, we have to predict whether a particular tweet, of which the text (occasionally the keyword and the location as well) is provided, indicates a  "Disaster" or "Non Disaster".
These categories typically correspond to whether a tweet is about a real-world disaster (such as a hurricane, earthquake, or fire) or about a non-disastrous event or topic.

## Part-1 Data Exploration and Preparation
• In this task, we have done exploration of datasets and the visualization of dataset in different ways such as histogram or bar plots and we analyze the frequency of keywords in Note-Book folder.

• We consider a number of text normalization processes, namely conversion to lowercase, removal of whitespaces, removal of punctuations, removal of unicode characters (including HTML tags, emojis, and URLs starting with http), removal of stop words, spelling correction, discardment of non-alphabetic words, and retention of relevant parts of speech and then we applied the Tokenize technique into individual words or tokens.

## Part-2 & 3 Feature Engineering and Model Selection, Model Evaluation & Validation
• Next, we implement the word frequencies, TF-IDF scores, and sentiment analysis.

• Finally, we use GloVe embedding for text representation.

• For each text representation setup, we apply a number of classifiers, namely logistic regression, random forest regression, neural network model and then we optimize hyperparameters techniques by using Grid search and compare their performances in terms of the average F1-score obtained from StratifiedKFold cross-validation. It achieves an average F1-Score of 0.8600

## Part-4 Deployment with Web Interface
Finally, we deployed the model successfully by using Deep learning techniques.
