# PracticalMLproject
Repo for practical ML final project

This is my repo for the Coursera / JHU Practical Machine Learning final project. The friendlier Github pages version is available here https://jimeharrisjr.github.io/PracticalMLproject/ 

## Summary

In this project, I examined the data from the Weight Lifting Exercises Dataset (http://groupware.les.inf.puc-rio.br/har#weight_lifting_exercises ) which includes a training set (labeled) and a test set (unlabeled). After dividing the training set into a test and validation set, I tried a number of different models, but two in particular had very good results (though both were extremely computationally and memory intensive): Random Forest and xgbTree (Extreme Gradient Boost Tree).

The Experiments below were run in R version 3.6.1 with Caret version 6.0-84, data.table version 1.12.8, doParallel version 1.0.15, dplyr version 0.8.3, e1071 version 1.7-3, foreach version 1.4.7, xgboost version 0.90.0.2, and randomForest version 4.6-14 on a 2019 16" MacBook Pro with an Intel i9 8-core, dual-threaded (16 virtual cores) processor and 64GB of RAM.

The results are documented in finalMLproject.Rmd, and finalMLproject.html or on Github pages here:  https://jimeharrisjr.github.io/PracticalMLproject/ 
