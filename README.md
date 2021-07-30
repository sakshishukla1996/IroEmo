# IroEmo
Implement Irony Detection over Emotion Classification 
# Introduction
The  aim  of  this  project  is  to  identify  if  ironyexists in multiple emotions  when classifying the textual  information. 

# Dataset
There are three directories with three different datasets. 
The first dataset belongs to the ISEAR directory. It has ISEAR dataset and is used in emotion classification.
The second dataset belongs to the TweetEval directory, it has the tweeteval data and is also used for emotion classification
The third is the directory for irony detector and is used for the same.

# Methodology
The methodolgies can be found in the files:
Emotion Classification:

EC_ISEAR_bert.ipynb is for emotion classification using bert and ISEAR data.

EC_ISEAR_bert_with_data_cleaning.ipynb is the exact same implementation with some normalization and data cleaning.

Emotion_classification.ipynb contains all the machine learning based methods for Emotion classification on ISEAR data.

RNN.ipynb is an implemetation of RNN on ISEAR data for Emotion classification.

Emotion_classification_bert.ipynb is an implementation of Emotion Classification using Bert embeddings and model.

Emotion_classification_bert_with_data_cleaning.ipynb is the exact same thing with data cleaning and some normalization techniques.


Irony detection:

There have been 3 different Embedding based techniques used to find out the best model for detecting irony.

Word_embedding.ipynb has the implementation of Word2vec and Fasttext.

Irony_detection_bert.ipynb has the implementation of Irony detection using bert model.

Irony_detection_bert_with_data_cleaning.ipynb does the exact same thing but along with that performs data cleaning and normalization.


# Result
Accuracy Metric

For Emotion Classification using TweetEval Data
Bert Base Uncased  without Data Cleaning: 0.8128

For Emotion Classification using ISEAR Data
Bert Base Uncased  without Data Cleaning: 0.7029

For Irony Detection using TweetEval Data
Bert Base Uncased  without Data Cleaning: 0.7184
