# Images_Recognition_using_SVM
This's a small project using SVM to classify the images type 

## Table of Contents
1. [General Info](#general-info)
2. [Requirements](#requirements)
3. [Model](#model)

### General Info
***
This's a Machine learning project for the year 2023
This's project about making the machine to classify the correct class of the iamges after seeing images from the same class before
In this project we have two folder, one for traning images and other one for testing the model
Because the data is small we used a smaple model like SVM rather than nueral network model


### Requirements
***
Python 3
seaborn 0.11.2
scikit-learn 0.24.2
numpy 1.22.4
matplotlib 3.4.3
Jupter notebook

### Model
***
1. First I readed the the images using imread then resized it using resize then extract the feature I can deal with using hog
2. After this I used GridSearchCV to pick the best parammters I can use in the SVM model to get the higher accuracy on the validition set
3. At last I used these parammters to predict the test data 
