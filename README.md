# Email Spam Detection Using Machine Learning

# Overview

This project aims to create a machine learning model that can effectively classify emails as either "ham" (not spam) or "spam." The model uses a dataset containing email labels and their corresponding text. Through preprocessing, vectorization, model training, and evaluation, the project seeks to accurately detect spam emails.

# Dataset

# The dataset contains the following columns:

label: The category of the email, either 'ham' or 'spam'.

text: The content or topics of the email.

label_num: A numeric representation of the label, where 'ham' is mapped to 0 and 'spam' is mapped to 1.

# Project Steps

Data Loading: Load the dataset from a CSV file.

Data Exploration: Visualize the distribution of ham and spam emails, and create word clouds for common words in each category.

Data Preprocessing: Convert the text data into numerical format using TfidfVectorizer.

Model Training: Train a Naive Bayes classifier (MultinomialNB) on the processed text data.

Model Evaluation: Evaluate the model's performance using accuracy, classification report, and confusion matrix. Visualize the confusion matrix and analyze important features.

Predictions: Make predictions on new email samples.

# Visualizations

# The project includes the following visualizations:

Countplot: Shows the distribution of ham and spam emails.

WordCloud: Displays the most frequent words in ham and spam emails.

Confusion Matrix Heatmap: Visualizes the model's performance.

# Important Features

The project identifies and displays the top 10 words that are most indicative of ham and spam emails, based on the log probabilities from the Naive Bayes model.

# How to Run

Clone the repository or download the code.

Place your dataset CSV file in the project directory.

Modify the path_to_your_dataset.csv in the code to the actual path of your dataset.

Run the Python script to execute the entire process, from data loading to model evaluation.

# Dependencies

Python 3.x

pandas

scikit-learn

seaborn

matplotlib

wordcloud

You can install the required libraries using:

# bash

Copy code

pip install pandas scikit-learn seaborn matplotlib wordcloud

# Example Output

Accuracy: A numerical value representing the model's accuracy.

Classification Report: Precision, recall, f1-score, and support for each class.

Confusion Matrix: A matrix showing true positives, false positives, true negatives, and false negatives.

Top Words: Lists of words most likely to predict ham and spam emails.

# Sample Prediction

python

Copy code

sample_text = ["Congratulations! You've won a lottery."]

# Prediction: Spam
License

This project is licensed under the MIT License - see the LICENSE file for details.

# Contact
For any questions or feedback, please reach out to [Nayan Dhurve] at [nayandhurve44@gmail.com].
