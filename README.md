{\rtf1\ansi\ansicpg1252\cocoartf2870
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Titanic Survival Prediction\
\
## Overview\
Binary classification project predicting passenger survival on the Titanic \
using the Kaggle Titanic dataset.\
\
## Approach\
- Performed exploratory data analysis to understand feature distributions\
- Handled missing values in Age and Embarked columns\
- Encoded categorical variables (Sex, Embarked)\
- Trained and compared Logistic Regression and Random Forest models\
- Achieved a public leaderboard score of 0.76555\
\
## Results\
| Model | Validation Accuracy |\
|-------|-------------------|\
| Logistic Regression | 81.56% |\
| Random Forest | 78.77% |\
\
## What I'd improve next\
- More feature engineering (extracting titles from Name column)\
- Hyperparameter tuning with GridSearchCV\
- Try XGBoost\
\
## Tools Used\
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook}