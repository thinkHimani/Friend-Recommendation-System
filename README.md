# Friend Recommendation System
Created a Friend Recommendation System using Graph Analysis as a part of the coursework for Mining Massive Datasets.

It has been observed that users are likely to connect with new users if there are some mutual connections already established.  Our main goal, hence, is to recommend to users based on different features and analyze which features are most to least important for a link to be present and recommended. 

## Dataset
Link: https://www.kaggle.com/c/FacebookRecruiting

The dataset consists of two columns -  source and destination.  Each row in the dataset is an edge in the graph.

## Implementation
1. [Exploratory Data Analysis](https://github.com/thinkHimani/Friend-Recommendation-System/blob/master/EDA.ipynb)
2. [PrepCode](https://github.com/thinkHimani/Friend-Recommendation-System/blob/master/PrepCode.ipynb)
4. [Featurization](https://github.com/thinkHimani/Friend-Recommendation-System/blob/master/Featurization.ipynb)
5. [Model Building](https://github.com/thinkHimani/Friend-Recommendation-System/blob/master/Models.ipynb)

## Conclusion


Plotting a graph that shows the importance of each feature in predicting the edge, follow back is seen to be the most important feature.

Our model classifies 24570 positive points as truly positive points and 21977 negative points as truly negative points in our test data.
