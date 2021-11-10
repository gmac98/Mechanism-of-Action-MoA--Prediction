# Mechanism of Action(MoA) Prediction
 The goal of this project is to classify drugs on the basis of biological activity using machine learning techniques.
 
Problem description:
We will use a dataset that combines gene expression and cell viability data. The data is based on a new technology that measures simultaneously (within the same samples) human cells’ responses to drugs in a pool of 100 different cell types (thus solving the problem of identifying ex-ante, which cell types are better suited for a given drug).
We will be predicting multiple targets of the Mechanism of Action (MoA) response(s) of different samples given various inputs such as gene expression data and cell viability data.

Outcome of the project:
Based on the MoA annotations, the accuracy of solutions will be evaluated on the average value of the logarithmic loss function applied to each drug-MoA annotation pair. We will be minimizing this log-loss value by using various models. We also expect to do an initial Exploratory Data Analysis on the initial dataset to provide more insights into the data.

Algorithms to be used:
The models we plan to use include the following -

--Multi Input ResNet Model

--Logistic Regression

--Neural Network

--SVM

--XGBoost

Libraries:
We expect to be working using Python. The following libraries will have to be / are expected
to be utilized –
-- numPy

-- Pandas

-- Keras

-- TensorFlow

-- sklearn

-- matplotlib

Dataset:

We will be using the MoA dataset from Kaggle.
https://www.kaggle.com/c/lish-moa/data
