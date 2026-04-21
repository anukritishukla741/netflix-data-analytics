# 🎬 Netflix Data Analytics & Machine Learning Project

## 📌 Overview
In this project, I analyzed the Netflix dataset to understand content trends and built a machine learning model to classify whether a title is a Movie or a TV Show.

The focus was not just on building a model, but on understanding the data and improving the model step by step.

## 📊 What I Did

### 🔹 Data Cleaning & Preparation

* Handled missing values in multiple columns
* Converted date formats and extracted features like `year_added`
* Cleaned and structured the dataset for analysis

### 🔹 Exploratory Data Analysis

* Compared distribution of Movies vs TV Shows
* Analyzed top contributing countries
* Studied how content has grown over the years
* Explored ratings distribution

### 🔹 Feature Engineering

* Selected relevant features such as country, rating, and release_year
* Applied one-hot encoding for categorical variables
* Scaled numerical features using StandardScaler

## 🤖 Machine Learning

### 🔹 Logistic Regression

* Built a baseline model
* Observed very high accuracy initially due to a dominant feature
* After removing that feature, achieved a more realistic accuracy of ~73%

### 🔹 Random Forest

* Used to capture more complex patterns
* Improved accuracy to ~75%


## 📈 Evaluation

* Accuracy Score
* Precision, Recall, F1-score
* ROC AUC Score
* Confusion Matrix visualization

## 🔍 Key Observations

* Movies are more common than TV Shows on Netflix
* Content growth increased significantly after 2015
* Peak content addition was around 2019–2020
* `release_year` is an important feature as it captures trends over time
* Ratings and country also influence predictions


## 🧠 What I Learned

* How to build an ML workflow from preprocessing to evaluation
* Why very high accuracy can be misleading
* Importance of evaluating models beyond accuracy
* How to interpret model behavior using feature importance


## 🛠️ Tech Stack

* Python
* Pandas
* Matplotlib & Seaborn
* Scikit-learn


## 🚀 Future Scope

* Try advanced models like XGBoost
* Perform hyperparameter tuning
* Build a dashboard or simple app for visualization

