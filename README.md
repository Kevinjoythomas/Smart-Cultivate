# 🌱 Cultivating optimal crop yields with Machine Learning! ☀️

## 📝📝 Description
### - This is a machine learning model that I made which provides the best suitable crop to grow based on many factors such as potassium, nitrogen, pH levels, etc 
### - Employed various machine learning algorithms, including Logistic Regression, K-Nearest Neighbors, Random Forest, etc to predict the most suitable crop for given environmental factors

## ⌛⌛ Dataset
### - You can download the data set through this link [https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset]
### - Since it is not a very large data set with extensive examples I used an 80% train and 20% testing split.

## 🎯🎯 Goal !!!
### -The goal of making this project is so that there is no soil in India going to waste 📈.

## 💻💻 Models
### The accuracies on the testing set of the models I used are the following
### Logistic Regression: 94.31% 
### from sklearn.linear_model import LogisticRegression
### K Nearest Neighbours: 97.72%
### from sklearn.neighbors import KNeighborsClassifier
### Gaussian Naive Bayes: 99.09
### from sklearn.naive_bayes import GaussianNB
### Decision Tree: 98.18%
### from sklearn.tree import DecisionTreeClassifier
### AdaBoost: 19.5%
### from sklearn.ensemble import AdaBoostClassifier
### XGBoost: 99.31%
### from xgboost import XGBClassifier
### Random Forests with Out-of-Bag:  99.54%
### from sklearn.ensemble import RandomForestClassifier

## 🎆🎆 Result
### At the end after numerous hyperparameter tuning the final model was finalized with a Random forest model with an out-of-bag method which had a 100% accuracy on the training set and a promising accuracy of 99.54% on the testing set😄😄. 
