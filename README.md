# AI_Research

Independent Research Project

Every year billions of dollars are lost on uninformed prop bets. This paper proposes a model to predict points per game in the NBA, which can help mitigate these losses using high-accuracy mathematical predictions. A novel method using a multi-layer perceptron built on individual and team statistics is described in this paper. The proposed model has an R2 of nearly 0.8, outperforming most publicly available models for the same, with the major difference being feature engineering and the implementation of a neural network. The proposed model is therefore suitable for further academic and practical research and application, both public and private.

## Dataset

A total of 15 variables were used in the dataset X. The data was scraped from NBAStuffer.com [2011]. To train the models, data from the 2010-11 NBA regular seasons was collected and compiled. Thus, the dimensions of X is 52692 × 15, where 52692 is the sum of the total number of players for each season from 2010-11 to 2019-20. The dataset was then separated randomly into a training and testing set (67% training and 33% testing).

                 

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
