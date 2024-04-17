# Machine Learning
 This repo contains all the assignments done in course ML at BTH
# Assignment 1
# Spam Classification using Concept Learning
This project implements a concept learner to classify spam emails using the Spambase Dataset. The aim is to implement Algorithm 4.1 and either Algorithm 4.2 or 4.3 from the main literature, without using any existing code except standard libraries.

# Dataset
The Spambase Dataset contains features extracted from emails, representing continuous attributes.

# Algorithms Implemented
+ Algorithm 4.1: Concept Learning: This algorithm forms a hypothesis space by considering each attribute's possible values and their combinations.
+ Algorithm 4.2: This algorithm refine the concept learner's output.

# Features
+ Preprocessing: Continuous to discrete transformation using binning.
+ Training: Implementation of the concept learner algorithm.
+ Testing: Classification of emails using the generated model.
+ Implementation Details
+ Language: Python
+ Libraries: NumPy, pandas, scikit-learn
+ Model Evaluation: Accuracy computation

# Usage
+ Download the Spambase Dataset from the provided link.
+ Ensure Python and required libraries are installed.
+ Place the dataset file (spambase.data) in the same directory as the code.
+ Run the code (spam_classification.py) to train the model and classify emails 


# Project Assignment 2
# Credit Score Classification with Machine Learning
This assignment 2 contains code and resources for a project focusing on credit score classification using machine learning techniques. Credit scoring is a crucial task in the financial sector, aiding institutions in assessing the creditworthiness of individuals. The goal of this project is to analyze and compare the performance of different machine learning models for credit score classification.

# Key Features:
+ Model Selection: Conducts a literature review to select appropriate machine learning algorithms for credit score classification.
+ Data Pre-processing: Cleans and transforms raw credit scoring data, handling null values, encoding categorical data, and scaling numerical data.
+ Model Training and Testing: Implements Logistic Regression, Support Vector Machine (SVM), and Random Forest models for classification, performing hyperparameter tuning and evaluating model performance.
+ Performance Evaluation: Utilizes accuracy and F1-score metrics to assess the performance of the trained models.
+ Results Analysis: Presents experimental results and analyzes the performance of each model to identify the most efficient classifier for credit score classification.

# Contents:
+ Code: Contains Python scripts for data pre-processing, model training, and evaluation.
+ Data: Includes the "Credit Approval Data Set" used for credit score classification.
+ Documentation: Provides detailed documentation on data pre-processing steps, model selection, and performance evaluation.
+ Results: Presents experimental results, including accuracy and F1-score metrics, in tabular and graphical formats.
