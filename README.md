
# Heart Stroke Prediction using KNN



## Abstract
Heart strokes are one of the leading causes of death worldwide. With the recent rise in deaths due to heart strokes in patients with covid symptoms and other illnesses, it is crucial to keep track of patients' health records. This project uses a dataset containing attributes such as familial health history, age, smoking status, gender, work type, and marriage status to predict the likelihood of a heart stroke.

We have chosen to use the K-Nearest Neighbor (KNN) algorithm for this project due to its simplicity and accuracy. The KNN algorithm is a non-parametric, supervised machine learning algorithm that can be used for both classification and regression problems. In this project, we will be using the KNN algorithm for classification.

## KNN Algorithm


The KNN algorithm is based on the principle of "similarity." Given a new data point, the algorithm calculates the distances between the new data point and all the points in the training data. The algorithm then finds the K nearest training data points and makes a prediction on the new data point based on a majority vote or weighted average.

The steps involved in the implementation of the KNN algorithm are:

1. Scaling of features if they have different scales
2. Calculation of distances between the new data point and all the points in the training data
3. Finding the K nearest training data points
4. Making the prediction on the new data point.


Classification: majority vote or weighted majority vote.

Regression: average or weighted average


## Advantages Of KNN



Advantages of KNN
1. No assumptions about data
2. Simple algorithm: easy to implement and easy to understand
3. Can be used for both classification and regression
4. Only several hyper-parameters required to implement such as the value of K, distance function, and the type of prediction (straightforward or weighted).




At the end of this project, we will display some accuracy metrics to evaluate the performance of the KNN algorithm.