Binary Classification Task of Ultrasound Images for Thyroid Nodule Malignancy 

Dataset used in training and testing from TN5000 - available here: https://www.nature.com/articles/s41597-025-05757-4#Sec4

The following 2 files approach the task from two different ML techniques: a regression model and a CNN. 
Train / validation / test sets are predetermined from the source data files to ensure standardized comparisons are enabled. 

"thyroid_regression" builds a logistic regression with 13 selected features, detailed within the code notes. 

"thyroid_cnn" builds a DenseNet 121 CNN model for classification, with an optional switch to compare to ResNet 50. 
Epoching, batch size, learning rate can all be edited within the code for hyperparameter tuning. 
