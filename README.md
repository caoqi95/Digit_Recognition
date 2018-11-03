# Digit_Recognition

This repo just for my project of Data Mining course. Which is using the .txt dataset and Decision Tree and MLP algorithm.

## Dataset

Given file is the handwritten digit data set (from 0 to 9) which has 10 classes.Each digit is binary image which is marked by 0 or 1 (1 is black, 0 is white). It is 2-dimensional image (24X18). You can make it in 1-dimensional image by consecutively attaching the rows or columns (432 dimensions; 432 features).

## Project requirement

Seperate the data set into 70% for training and 30% for testing randomly from each class.

1) Use MLP for classification using 423-dimension data set.

2)

    2-1) Apply the decision tree for classification using 423-dimension data set.
    
    2-2) Select the features which appears in the decision tree nodes.
    
    2-3) Use the new data set which is composed of the features selected in 2-2) for classification with MLP.

Compare the result from 1), 2-1) and 2-3).

For this project, find and apply the optimal or proper number of hidden units (and/or hidden layers).

## Solution

+ MLP_Part for requirement 1)

+ DT_Part for requirement 2-1) ~ 2-3)
