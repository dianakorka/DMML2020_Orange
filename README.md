# DMML2020_Orange
## Real or Not? NLP with Disaster Tweets

## Project description
In this project, as part of the UNIL data mining and machine learning class, we were challenged to build a Machine Learning model that can predict which tweets are about a real disaster and which are not, using various natural language processing models. The project topic is based around a Kaggle competition also posted on AIcrowd here:https://www.aicrowd.com/challenges/final-project-of-the-data-mining-and-machine-learning-course. 

## Data
The labelled training dataset is in the data folder, as well as an unlabelled test set.

## Submissions
To test accuracy on a new unseen dataset, submission have to be in the format presented in the data folder of this project.

## Video presentation
Here is a presentation of the work we have done for this project: https://www.youtube.com/watch?v=OQinnPFsxtI&feature=youtu.be

## Progression

Week 1

    Discovered the project
    Created Repository with test and training data
    Created a Slack channel for discussion
    Started the notebook, computed the base rate (57%) on 6471 samples in the training data

Week 2

    Ran basic prediction with 0.8 accuracy on our test part of the training data
    Submitted and got 0.819 test accuracy
    Did the EDA : top keywords and locations, top keywords and locations with the most real and fake tweets
    Delete doubling, usernames and hastags and see a slight decrease in accuracy (0.8013)

Week 3

    pooling of our codes
    testing of vectorizer configs
    testing of the RandomForest, with no improvement for the moment (accuracy: 0.792)

Week 4

    optimizing the hyperparameters of logistic regression, tf-idf and random forest
    testing KNN, with still no improvement from logistic regression for the moment (accuracy : 0.72)
    searched for stopwords and slangs lists
    None of our submissions were better than the first one

Week 5

    testing new stopwords (accuracy: 0.8178)
    reorganisation and presentation of the code
    testing dimension reduction and features engineering (accuracies: 0.8015 and 0.8131)
    testing NLTK and Doc2Wword instead of TF-IDF (accuracies: 0.8178 and 0.81)
    creation of the support for the presentation
