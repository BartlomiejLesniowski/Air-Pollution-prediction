# Data Science - Air-Pollution-prediction

Dataset can be downloaded from Kaggle.com - https://www.kaggle.com/datasets/mujtabamatin/air-quality-and-pollution-assessment/data

# About Dataset from kaggle.com
This dataset focuses on air quality assessment across various regions. The dataset contains 5000 samples and captures critical environmental and demographic factors that influence pollution levels.

The dataset contains 10 features including target feature - Air Quality.


# Goal and methodology

My goal of this project is to achieve as high as possible model accuracy. To find the best classification model I used couple models:
 - SVC
 - Decision Tree Classifier
 - Random Forest Classifier
 - KNeighbors
 - AdaBoost

Additionally I performed EDA. I noticed that with higher concentration of particulate matter levels, CO, NO2 and SO2 is correlated with high air pollution. 

Surprisingly, high temperature and high humidity are also highly correlated with high air pollution, however it can be caused by inbalance within target classes.


As dataset is higly skewed with many outliers within almost every feature, I decided to drop outliers and train models.

# Results

The accuracy results in comparison with other models:
 - SVC - 0.791
 - Decision Tree Classifier - 0.939
 - Random Forest Classifier - 0.964
 - KNeighbors - 0.742
 - AdaBoost - 0.418
