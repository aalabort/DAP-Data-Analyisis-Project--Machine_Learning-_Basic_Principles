# DAP Data Analyisis Project - Machine Learning Basic Principles (Aalto University - November 2018)

The data analysis project involves the design of a complete machine learning solution. In
particular, the project revolves around the task of identifying the music genre of songs. This
is useful as a way to group music into categories that can be later used for recommendation
or discovery. The problem of music genre classification is difficult: while some genres
distinctions are fairly straightforward (e.g. heavy metal vs classical), others are fuzzier (e.g.
rock vs blues).

Create a predictor h(x) for each genre Y, which takes the features x and maps it to a probability h(x) that the genre is "rock" (e.g.) or not.

The dataset which is provided to solve this task contains preprocessed audio information. In particular, the raw audio signals have been transformed to carefully chosen features.

The data is split into two datasets: a training data set with 4363 songs, and a test set dataset  with 6544 songs. Each song has 264 features, and there are 10 possible classes in total.

The dataset is a custom subset of the Million Song Dataset, and the labels were obtained from AllMusic.com. For simplicity, each song has been assigned only one label that corresponds to the most representative genre. The 10 labels are:

1 'Pop_Rock'
2 'Electronic'
3 'Rap'
4 'Jazz'
5 'Latin'
6 'RnB'
7 'International'
8 'Country'
9 'Reggae'
10 'Blues'

The features provided are a summary representation of the 3 main components of music:
timbre, pitch (melody and harmony) and rhythm. 
