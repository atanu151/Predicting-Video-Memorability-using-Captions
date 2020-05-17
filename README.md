# Predicting-Video-Memorability-using-Captions
The task of Predicting Media Memorability is part of the MediaEval Multimedia Assessment benchmarking initiative. The objective of this task is to automatically predict a memorability score for a video that will represent its probability of being remembered. An extensive dataset of 6000 short videos along with its pre-computed state-of-the-art features is provided for modelling purpose. The memorability of videos is assessed through recognition tests for both short-term and long-term memory which are provided as ground truth scores for training and testing the models.
In this paper, three main methods for text processing are explored for generating features from captions. CountVectorizer, TfidfVectorizer and One-hot encoding are the techniques that produced input for the prediction models. The features are fed into three different models to predict short-term and long-term memorability scores and evaluated using Spearman’s correlation score as a standard measure. An optimized ensemble model is built using the best scores of two different models after analysing and comparing the models.
