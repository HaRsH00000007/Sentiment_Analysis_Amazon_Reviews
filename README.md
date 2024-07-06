# Sentiment_Analysis_Amazon_Reviews

Amazon Reviews Sentiment Analysis
This repository contains an end-to-end NLP project focused on sentiment analysis of Amazon reviews. The goal is to classify reviews as positive, neutral, or negative. The project includes data preprocessing, model building, and deployment through a Flask web application.

Table of Contents :

-> Introduction

-> Dataset

-> Installation

-> Usage

-> Model Building

-> API and Web Application

-> Results

-> Contributing

-> License

Introduction

This project explores sentiment analysis using Amazon reviews. The classifier predicts whether a review has a positive, neutral, or negative sentiment. The model is deployed as an API and a web application using Flask.

Dataset :

The dataset contains Amazon reviews with their respective sentiment labels. Data preprocessing steps include cleaning, tokenization, stemming, and removing stopwords.

Installation

To get started, clone the repository and install the required libraries:

bash
Copy code
git clone https://github.com/yourusername/amazon-reviews-sentiment-analysis.git
cd amazon-reviews-sentiment-analysis
pip install -r requirements.txt
Usage

Preprocess the data: Run the preprocessing script to clean and prepare the data.
Train the model: Execute the training script to build the sentiment analysis classifier.
Run the web application: Start the Flask web application to interact with the model through a web interface.

Model Building

Libraries Used

numpy

pandas

matplotlib

seaborn

nltk

sklearn

wordcloud

xgboost

pickle

Steps :

-> Exploratory Data Analysis (EDA): Visualized data distributions and created word clouds.

-> Data Preprocessing: Cleaned text data, performed tokenization, stemming, and removed stopwords.

-> Feature Engineering: Used CountVectorizer to convert text to numerical features.

-> Model Training: Trained various classifiers including RandomForest, DecisionTree, and XGBoost.

-> Model Evaluation: Evaluated models using cross-validation, confusion matrices, and accuracy scores.

API and Web Application :

A Flask web application is built to interact with the trained model. The web application allows users to input review text and get sentiment predictions.

Results

The model achieved satisfactory accuracy in predicting the sentiment of Amazon reviews. Detailed results and performance metrics are available in the results section of the repository.

Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss any changes or improvements.

License

This project is licensed under the MIT License.


![Screenshot 2024-07-06 092933](https://github.com/HaRsH00000007/Sentiment_Analysis_Amazon_Reviews/assets/124857047/edff6f2c-8faa-433c-a107-05350125080d)


![Screenshot 2024-07-06 092843](https://github.com/HaRsH00000007/Sentiment_Analysis_Amazon_Reviews/assets/124857047/0a84d01e-70c2-49be-b06f-c99f33279631)![Screenshot 2024-07-06 092903](https://github.com/HaRsH00000007/Sentiment_Analysis_Amazon_Reviews/assets/124857047/f8212b8b-aab3-4b7a-9c19-cfac71feb524)

![Screenshot 2024-07-06 093145](https://github.com/HaRsH00000007/Sentiment_Analysis_Amazon_Reviews/assets/124857047/26c89656-741b-404e-858e-132c30905349)
![Screenshot 2024-07-06 093211](https://github.com/HaRsH00000007/Sentiment_Analysis_Amazon_Reviews/assets/124857047/5e086781-7e98-4cfe-8e9c-f437ef90511e)
