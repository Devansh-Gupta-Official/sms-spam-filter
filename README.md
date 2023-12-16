# Email Spam Classification

This repository contains an Python Notebook (spam_filter.ipynb) that demonstrates the process of email spam classification using machine learning techniques.

## Overview
The dataset (emails.csv) consists of email text and labels indicating whether an email is spam or not.
### Dataset Description
- text: Email text content
- spam: Binary label (1 for spam, 0 for non-spam)

## Contents
1. Importing Libraries and Dataset
The notebook begins by importing necessary Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and reading the dataset into a Pandas DataFrame.

2. Visualizing the Dataset
Visual representation of the dataset is provided, showing the distribution of spam and non-spam emails using count plots.

3. Data Preprocessing
Demonstrates the process of converting text data into numerical format using Count Vectorizer.

4. Training the Model
Utilizes the Multinomial Naive Bayes classifier to train the model on the dataset.

5. Evaluating the Model
Evaluates the model's performance on a test set using metrics like precision, recall, and F1-score. Confusion matrices and heatmap visualizations are also included.

6. Creating Testing and Training Dataset
Demonstrates the process of splitting the dataset into training and testing subsets for model evaluation.
