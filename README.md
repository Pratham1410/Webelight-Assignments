﻿# Webelight-Assignments
# Machine Learning

Task 1:<br>
In Task 1, I conducted Exploratory Data Analysis (EDA) on the dataset. Upon analysis, it became evident that the data was highly imbalanced, with very few instances of class 1 compared to classes 2 and 0 in predicting diabetes.I employed a Random Forest model initially, achieving an accuracy of 82.14% post-tuning. However, leveraging Gradient Boosting increased the accuracy slightly to 84.25%. Despite these improvements, the model consistently failed to predict class 1 due to the data imbalance issue. To mitigate this, I developed a neural network model with custom handling for imbalanced data, using a specialized loss function (cost-sensitive learning). This approach was aimed at improving the classification of the minority class, thus it result in increased misclassification of the majority class, thus resulting in less overall accuracy. The confusion matrix provided a clearer assessment of the model's performance.

Task 2:<br>
For Task 2, I applied K-means clustering to the data. Using both the Elbow method and Silhouette analysis, I determined the optimal number of clusters. Subsequently, I performed K-means clustering with the identified optimal number of clusters and calculated the correlation matrix. Identifying columns with the highest correlations, particularly focusing on Phenols and Flavanoids, I visualized the clusters based on these correlations.

# Recommendation Model Task:

Task 3:<br>
For the Movie Recommendation model, I implemented Collaborative Filtering using cosine similarity. To enhance prediction accuracy, I integrated it with a Neural Network model trained specifically for this task.

# Computer Vision Task:

Task 4:<br>
In this task, I mainly utilized OpenCV2 and Matplotlib for majority of tasks.For Custom object detection i used pre-trained resnet model alongwith coco classes.
