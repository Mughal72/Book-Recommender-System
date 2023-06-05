# Book-Recommender-System
## Concept used to build the model.pkl file : NearestNeighbors
1 . Load the data

2 . Initialise the value of k

3 . For getting the predicted class, iterate from 1 to total number of training data points

4 . Calculate the distance between test data and each row of training data. Here we will use Euclidean distance as our distance metric since it’s the most popular method.

5 . Sort the calculated distances in ascending order based on distance values

6 . Get top k rows from the sorted array

## Data Set Link
https://www.kaggle.com/datasets/ra4u12/bookrecommendation
