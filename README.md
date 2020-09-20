# Hand Posture Recignition

This project implements different ML models to recognize hand postures from the given data (described below). 5 models are trained:
1. Naive Bayes classifier
2. Support Vector Mahcine
3. Stochastic gradient descent
4. Perceptron Learning classifier
5. Random Forest classfier.

## Dataset description

The hand posture dataset consists of data from unlabeled markers on the fingers of a glove in a motion capture environment giving the x, y, z coordinate axes values for 5 different hand postures. Each data point has between 9 and 36 marker values. The number varies as some markers have been occluded by other fingers or portions of the hand, and marker values have not been collected. Due to this there are many missing points in the raw data and hence it cannot be directly used in this form for the model training.

A meaningful dataset has been defined with 13 features (Linear dataset) and an expanded dataset has been defined with 60 features (Expanded dataset). Both have been used to train models and also the best features among the defined ones have been used to train the models.

## Results:

![](/result.JPG)


