# AI_Research

Independent Research Project

Every year billions of dollars are lost on uninformed prop bets. The proposed model can help mitigate these losses using high-accuracy mathematical predictions. A novel method using a multi-layer perceptron built on individual and team statistics is described in this paper. The proposed model has an R2 of nearly 0.8, outperforming most publicly available models for the same, with the major difference being feature engineering and the implementation of a neural network. The proposed model is therefore suitable for further academic and practical research and application, both public and private. The model can be freely used for sports betting, fantasy or evaluating player performance.

An interactive applet can be found on my blog at https://www.stuff-blog.com/sports/predicting-stats-in-the-2021-22-nba-season-using-neural-networks.

## Dataset

A total of 15 variables were used in the dataset X. The data was scraped from NBAStuffer.com [2011]. To train the models, data from the 2010-11 NBA regular seasons was collected and compiled. Thus, the dimensions of X is 52692 × 15, where 52692 is the sum of the total number of players for each season from 2010-11 to 2019-20. The dataset was then separated randomly into a training and testing set (67% training and 33% testing). The relevant scraped data can be found in .csv files in the stats folder.
