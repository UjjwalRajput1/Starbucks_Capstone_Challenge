# Data Scientist Nanodegree Starbucks Capstone Challenge

This repository has all the code and report for my Data Scientist Nanodegree Starbucks Capstone project including profile.json,portfolio.json,transcript.json,readme,and .ipynb file.
Starbucks Capstone Challenge: Using Starbucks app user data to predict effective offers

# 1. Installations
This project was written in Python, using Jupyter Notebook on Anaconda. The relevant Python packages for this project are as follows:

- sklearn.model_selection (train_test_split module)
- sklearn.preprocessing (StandardScaler, PolynomialFeatures)
- math
- json
- pandas
- numpy
- matplotlib
- time
- from sklearn.tree (DecisionTreeClassifier,DecisionTreeRegressor)
- sklearn.ensemble (RandomForestClassifier)
- sklearn.metrics (mean_squared_error,classification_report)
- sklearn.linear_model (Ridge)
- sklearn.model_selection (GridSearchCV)

# 2. Project Motivation
This project is the last Capstone project of my Data Scientist nanodegree . As students in the nanodegree, we have the option to take part in the Starbucks Capstone Challenge.
For the challenge, Udacity provided simulated data that mimics customer behavior on the Starbucks rewards mobile app.

In this project i have answered two business problems as -

  - a. What are the main drivers of an effective offer on the Starbucks app?
  - b. Could the data provided, namely offer characteristics and user demographics, predict whether a user would take up an offer?

To answer the above 2 questions, I created 3 models for the data on the 3 offer types provided. The three offers are: Discount(discount with purchase), Buy One Get One Free (BOGO), and Informational (provides information about products).

As a brief summary of my findings:
- For Question 1, the feature importance given by all 3 models were that the tenure of a member is the biggest predictor of the effectiveness of an offer. Further study would be able to indicate what average tenure days would result in an effective BOGO offer.

- For Question 2,my decision to use 3 separate models to predict the effectiveness of each offer type ended up with good accuracy for the 2 of the models (82.83% for BOGO and 87.35% for discount), while slightly less accurate performance for another informational offers (75.3%). However, I would regard 75% as acceptable in a business setting, as for informational offers, there is no cost involved to inform users of a product. Meanwhile, an 80% and above accuracy in a business setting would be acceptable to show offers to people, even if the model misclassifies a few, the overall revenue increase might justify the few mistakes.

# 3. File Descriptions
The report of my project is called 'Starbucks Capstone Challenge - Using Starbucks app user data to predict effective offers.ipynb'. 
The data used in the project is in the files portfolio.json, profile.json and transcript.json. 

# 4. Licensing, Authors, Acknowledgements, etc.

Data for coding project was provided by Udacity.
