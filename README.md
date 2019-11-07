# Dead-or-Alive
Predicting whether a passenger on board HMS Titanic survived the disaster or not.

DATA SOURCE:
The Titanic Dataset was downloaded from Kaggle and the results were submitted to the competition "Titanic: Machine Learning from Disaster"

MODELS USED:
I have used multiple models for predicting the fate of an individual. 
The three files uploaded in my repository have the following Regression models:

1. Part 1:
    Linear Regression;
    Random Forest Classifier;
    Support Vector Machines;
    Deep Neural Network;
2. Part 2:
    Deep Neural Network
3. Part 3
    Simple Ensemble Model (Stacking)
    
RESULT (Accuracy in Percent):
1. Part 1:
    Linear Regression:          0.75119;
    Random Forest Classifier:   0.76076;
    Support Vector Machines:    0.74641;
    Deep Neural Network:        0.77990;
2. Part 2:
    Deep Neural Network:        0.77990
3. Part 3:
    Simple Ensemble Model (Stacking):   0.79425


MORE ABOUT SIMPLE ENSEMBLE MODEL (STACKING):
Algorithms which combine multiple Machine Learning techniques to decrease variance (by Bagging), decrease bias (by Boosting) and improve predictions (by Stacking)

STACKING:
It combines multiple models which are trained on the original training data and their outputs are used as an input for the meta-model.
