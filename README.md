AI-Based Spam Email Detection System
Project Overview

This project implements a hybrid spam email detection system developed as part of the AI Systems Engineering (CMP-L044) module. The system combines rule-based filtering, classical machine learning, and transformer-based models to classify emails as Spam or Not Spam.

The aim is to design a system that is accurate, robust, computationally efficient, scalable, and adaptable to evolving spam patterns such as concept drift and adversarial behaviour.

Features

The system includes the following components:

Text preprocessing and cleaning pipeline
TF-IDF feature extraction
Baseline models including Naive Bayes and Logistic Regression
Cross-validation and evaluation metrics
Hybrid rule-based and machine learning classification
Transformer-based model using DistilBERT
Visual analysis including text length distribution and word clouds
Final prediction system that outputs Spam or Not Spam
Exportable prediction results in CSV format
System Architecture

The system follows a multi-stage hybrid pipeline:

Data Ingestion
The system accepts a CSV dataset with flexible schema handling.
Preprocessing
Text is cleaned through lowercasing, removal of punctuation, and normalization.
Feature Engineering
TF-IDF vectorization is applied to transform text into numerical features.
Classification Layer
A rule-based filter identifies obvious spam messages.
A Logistic Regression model performs primary classification.
A transformer model (DistilBERT) captures contextual meaning for complex cases.
Decision Logic
The final classification combines outputs from all components to produce a single decision.
Output
The system outputs a final prediction of Spam or Not Spam and can export results.
Evaluation Metrics

The system is evaluated using standard classification metrics:

Accuracy
Precision
Recall
F1 Score
ROC AUC
Confusion Matrix

Cross-validation is used to ensure robustness and reliability of results.

Dataset

The dataset used is a spam email dataset in CSV format containing labeled messages classified as Spam or Not Spam.

The system is designed to automatically adapt to different dataset structures by detecting relevant columns dynamically.

Installation and Setup

Clone the repository:

git clone https://github.com/your-username/spam-detection.git

cd spam-detection

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook spam_detection.ipynb

How to Run
Upload the dataset when prompted in the notebook.
Execute all cells sequentially.
View outputs including model performance, visualisations, and predictions.
Example Prediction

predict_email("Congratulations! You have won a free prize!")

Output:
Spam

Output

The system generates a file named:

final_spam_predictions.csv

This file contains:

Email text
Actual label
Predicted label
