# Twitter Sentiment
Machine Learning Model for NUS IT1244 Group Project

## Introduction
This project explores the application of Machine Learning (ML) and Deep Learning (DL) techniques to perform sentiment analysis on twitter posts. The goal is to classify the sentiment of a written tweet as positive or negative. A deeper understanding of sentiment trends can benefit businesses in refining marketing strategies, assist policymakers in gauging public opinion on key issues, and help researchers improve sentiment analysis models.

## Team Members
* Albertus Frederick Ashali
* Irving Tan
* Gin Jing Long Jack
* Goh Peng Kerng

## Project Overview
This project explores Machine Learning (ML) and Deep Learning (DL) techniques for sentiment analysis (SA) of tweets. The goal is to classify tweets into positive/negative sentiments by leveraging linguistic and contextual patterns. Key contributions include:

Comparative analysis of traditional ML models (Logistic Regression, Naïve Bayes, KNN) and DL architectures (BERT-based neural networks).

A custom cluster-based DL model for specialized sentiment classification.

Optimization strategies (AdamW, hyperparameter tuning, efficiency metrics) to enhance performance.

## Usage
Download the required libraries in requirements.txt.

Run the notebooks in this order:
### 1. Exploratory Data Analysis and Cleaning
Cleaning the data and did some basic feature selection at this step.
### 2. Logistic Regression (Baseline)
Using features selected from 1., ran a baseline Logistic Regression model.
### 3. Multinomial Naive Bayes (TF-IDF)
Utilising another model using TF-IDF encoding.
### 4. Random Forest Feature Selection and Finalised ML
Utilised different encodings such as Bag of Words, TF-IDF, VADERS and a combination of the basic feature selection in 1. and used Random Forest to select the best encoding. With that, we improve on the ML models (Logistic Regression, MUltinomial Naive Bayes, KNN) and used hyperparameter optimisation on each of the models based on accuracy. 
### 5. Neural Network
This step focuses on DL techniques to improve sentiment classification performance beyond traditional ML models. Defined custom parameters such as Accuracy Efficiency = Validation Accuracy / Number of Parameters as an efficiency metric. Lastly, utilised a custom model: Cluster-Based Deep Learning inspired by the Mixture of Experts (MoE) framework, which combines both DL and ML frameworks.
