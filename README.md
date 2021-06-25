# AI_Research

Independent Research Project

say you have 12 sessions

## Dataset

This section describes what the data is doing. Please describe the dimension of the data. What are the variables? What type of analysis are we looking at? (2 sessions)

- Motivation: why this data set is interesting/important/...?
- Example 1: image recognition => technology: we train an AI to classify / recognize the digits in a picture => if successful, we can deploy the technology in traffic cameras and we can trace the license plate if a traffic incidence happened => community impact
- Example 2: image recognition => technology: we train an AI to recognize hand gestures in the picture / video => 
                 scenario (i): deploying this AI to play rock, paper scissors
                 scenario (ii): deploying this AI to recognize the American Sign Language in order to communicate with the deaf people
                 
Resources:
- UCI Machine Learning Repository: click [here](https://archive.ics.uci.edu/ml/index.php)
- Paper with Code: click [here](https://paperswithcode.com/datasets)

Steps to take:
- Pick a source from above and download a data (try 3-5 datasets)
- Load in your favorite programming language: say python, panda dataframe, numpy, etc... see plot the shapes, head of the table, plot a few graphs (use this link as an example: [here](https://www.kaggle.com/zachgold/python-iris-data-visualizations)
- Try build a roadmap: 
         for each data: build the following => what is the data => what is the potential technology => motivation: why is it interesting?

Ex: Iris data set => this data describes 4 features of flowers and there are 3 different types of flowers => technology: build an AI to recognize the type of flowers by reading in the 4 features I provide => Motivation: for plant lovers, we can design an app so that the users can enter the width and length to determine what flowers they are planting

## Benchmark

This section does literature review. Suppose a dataset is chosen. This section covers some important models or algorithms that are currently performing well in the literature and briefly discuss their advantages and disadvantages. (this is scattered throughout the program, but I am expecting 1 sessions)
- Model 1: Decision Tree => 96% (this is done)
- Model 2: 70% why it's bad 
- Model 3: xxxx
- take some notes ...

## Proposed Model/Algorithm

This section introduces the proposed model. This is the model that you designed. It could be an upgrade of the existing model. It could also be a brand new model you newly designed. (4-5 sessions, a little more than a month)
- it could have coding
- and simulation

## Application

This section explains how to deploy your proposed model or algorithms on the dataset you mentioned in the beginning. In this case, you can say the lab procedure and prediction performance. (3-4 sessions, close to but less than a month)

Lab procedure:
- what is the training set => it is a portion (randomly selected) from the data you collect and this is the part of the data you use to train your model
- what is the testing set => use the models trained from the training set and try to predict on the test set (the portion of the data that is not used in training) to see how good the performance is

Prediction Performance:
- if it's classification, we use accuracy <= this metric checks how many correct answers your model has (the more the better)
- if it's regression, we track errors (one famous function is called: mean square error) <= this metric checks how many mistakes your model has made (the less the better)
