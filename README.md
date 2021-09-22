# Data-Analysis-Spark-Hadoop
Big Data Analysis with Python, Spark and Hadoop.

## 1. Building a word count application
Write code that calculates the most common words in the Complete Works of William Shakespeare.
* Part 1: Creating a base DataFrame and performing operations 
* Part 2: Counting with Spark SQL and DataFrames
* Part 3: Finding unique words and a mean value
* Part 4: Apply word count to a file
```
sentences:

0 - project gutenbergs the complete works of willi...
1 - ...
2 - this ebook is for the use of anyone anywhere i... 
3 - most other parts of the world at no cost and w... 
4 - whatsoever you may copy it give it away or re...
...
```
```
+----+--------+
|word|count(1)|
+----+--------+
| the|   30205|
| and|   28386|
|   i|   21949|
|  to|   20923|
|  of|   18822|
|   a|   16182|
| you|   14437|
|  my|   13180|
|  in|   12232|
...
+----+--------+
```

https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/PD1.ipynb

## 2. Web Server Log Analysis

Server log analysis is an ideal use case for Spark. It's a very large, common data source and contains a rich set of information. Spark allows you to store your logs in files on disk cheaply, while still providing a quick and simple way to perform data analysis on them.

* Part 1: Introduction and Imports
* Part 2: Exploratory Data Analysis
* Part 3: Analysis Walk-Through on the Web Server Log File 
* Part 4: Analyzing Web Server Log File
* Part 5: Exploring 404 Response Codes

![2-1](https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/images/2-1.png)

![2-2](https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/images/2-1.png)

https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/PD2.ipynb

## 3. Power Plant Machine Learning Pipeline Application

Using Machine Learning models to predict power plant power output.

* Part 1: Business Understanding 
* Part 2: Load Your Data
* Part 3: Explore Your Data
* Part 4: Visualize Your Data
* Part 5: Data Preparation
* Part 6: Data Modeling
* Part 7: Tuning and Evaluation

![3-1](https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/images/3-1.png)

![3-2](https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/images/3-2.png)

https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/PD3.ipynb

## 4. Predicting Movie Rating

One of the most common uses of big data is to predict what users want. This allows Google to show you relevant ads, Amazon to recommend relevant products, and Netflix to recommend movies that you might like. In this section you will use Apache Spark to recommend movies to a user. You will start with some basic techniques, and then use the Spark ML (https://spark.apache.org/docs/latest/api/python/pyspark.ml.html) library's Alternating Least Squares method to make more sophisticated predictions.

* Part 0: Preliminaries
* Part 1: Basic Recommendations 
* Part 2: Collaborative Filtering 
* Part 3: Predictions for Yourself

![4-1](https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/images/4-1.png)

https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/PD4.ipynb

## 5. Click-Through Rate Prediction

This section covers the steps for creating a click-through rate (CTR) prediction pipeline.

* Part 1: Featurize categorical data using one-hot-encoding (OHE) 
* Part 2: Construct an OHE dictionary
* Part 3: Parse CTR data and generate OHE features
* Part 4: CTR prediction and logloss evaluation
* Part 5: Reduce feature dimension via feature hashing

![5-1](https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/images/5-1.png)

https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/PD5.ipynb

## 6. Prediction of the Release Year of a Song

The goal is to train a linear regression model to predict the release year of a song given a set of audio features. The subset has 6,724 samples out of 515,345 in the original dataset. This section covers a common supervised learning pipeline.

* Part 1: Read and parse the initial dataset Visualization 1: Features Visualization 2: Shifting labels
* Part 2: Create and evaluate a baseline model Visualization 3: Predicted vs. actual
* Part 3: Train (via gradient descent) and evaluate a linear regression model Visualization 4: Training error
* Part 4: Train using SparkML library and tune hyperparameters via grid search * Visualization 5: Best model's predictions
Visualization 6: Hyperparameter heat map
* Part 5: Add interactions between features

![6-1](https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/images/6-1.png)

![6-2](https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/images/6-2.png)

https://github.com/SeanZheng21/Data-Analysis-Spark/blob/main/PD6.ipynb