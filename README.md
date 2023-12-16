# Email Spam Classification

This repository contains an Python Notebook (spam_filter.ipynb) that demonstrates the process of email spam classification using machine learning techniques.

## Problem Statement
- The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.

- The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

## Overview
The dataset (emails.csv) consists of email text and labels indicating whether an email is spam or not.
### Dataset Description
- text: Email text content
- spam: Binary label (1 for spam, 0 for non-spam)

## Contents
**1. Importing Libraries and Dataset**
In this section of the notebook, the necessary Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn are imported. Additionally, it loads the dataset into a Pandas DataFrame for further analysis.

**2. Visualizing the Dataset**
Visual representations like count plots are utilized to provide insights into the dataset's composition. This includes showcasing the distribution of spam and non-spam emails, aiding in understanding the dataset's characteristics.

**3. Data Preprocessing**
This section focuses on preparing the text data for model training. It demonstrates the process of converting raw text data into a numerical format suitable for machine learning algorithms using techniques like Count Vectorization.

**4. Training the Model**
Utilizes the Multinomial Naive Bayes classifier to train the model on the preprocessed dataset. This step involves fitting the model on the training data to learn patterns and relationships between the features and the target (spam or non-spam).

**5. Evaluating the Model**
The model's performance is evaluated using a test set that wasn't used during training. Metrics such as precision, recall, F1-score, and accuracy are calculated. Confusion matrices and heatmap visualizations are generated to provide a deeper understanding of the model's performance.

**6. Creating Testing and Training Dataset**
Demonstrates the process of splitting the dataset into training and testing subsets. This step ensures a fair evaluation of the model's performance by using separate data for training and testing.

## Usage
### Requirements
- Python 3.x
- Jupyter Notebook
- Required libraries (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

### Steps to Run
1. Clone this repository.
2. Ensure all required libraries are installed.
3. Open spam_filter.ipynb using Jupyter Notebook.
4. Run the cells in sequential order.

## Files Included
- spam_filter.ipynb: Jupyter Notebook containing the entire code and analysis.
- emails.csv: Dataset file containing email text and spam labels.

## Results
The model achieves an accuracy of approximately **99%** on the test set, demonstrating robust performance in classifying spam and non-spam emails.
