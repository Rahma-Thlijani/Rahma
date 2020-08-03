# Anticipating Youtube Videos' Views 
Data science project that uses deep learning and multiple linear regression aiming to predict the number of views for youtube videos.
## Data Description
We have two datasets in this project: "StatsVideosXALL.csv" (for the features) and "StatsVideosXALL.csv" (for the output).
The datasets has 3365 rows and 4 columns: Likes, Dislikes, Subscribers and Views, they related to each youtube video. 
## Project Overview
In this project will apply supervised learning techniques on youtube data to predict the number of views of a video considering multiple features. 
To accomplish this, we will compare 2 models: Multiple Linear Regression and Deep Neural Network. In addition, we will evaluate each model based on the MAE
the RMSE and the R2_Score.
## Project Steps
You will first process explore the data by selecting a small subset to sample and determine if any product categories highly correlate with one another. Afterwards, you will preprocess the data by scaling each product category and then identifying (and removing) unwanted outliers. With the good, clean customer spending data, you will apply PCA transformations to the data and implement clustering algorithms to segment the transformed customer data. Finally, you will compare the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes.

Things you will learn by completing this project:

How to apply preprocessing techniques such as feature scaling and outlier detection.
How to interpret data points that have been scaled, transformed, or reduced from PCA.
How to analyze PCA dimensions and construct a new feature space.
How to optimally cluster a set of data to find hidden patterns in a dataset.
How to assess information given by cluster data and use it in a meaningful way.

## Conclusion / Results
Two different learning algorithms (Multiple Linear Regression and Deep Neural Network) were tested, and we have evaluated their performance.
The best prediction performance was achieved with the Deep Neural Network model, and resulted in the following metrics:

* Mean Absolute Error (MAE): 12317109.74
* Root mean squared error (RMSE): 56406118.44
* R-squared Score (R2_Score): 0.8038


