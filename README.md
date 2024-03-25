# finalCapstone

**Amazon Product Reviews Sentiment Analysis**

This project is a sentiment analysis application that analyzes customer reviews for Amazon products. It uses natural language processing techniques to classify the sentiment 
of each review as positive, negative, or neutral.

**Table of Contents**

Project Description
Installation
Usage
Credits

**Project Description**

The Amazon Product Reviews Sentiment Analysis project is designed to help businesses and individuals gain insights into customer satisfaction with their products.
By analyzing the sentiment of customer reviews, companies can identify areas for improvement, address customer concerns, and make data-driven decisions to enhance 
their products and services.
The application uses the TextBlob library for sentiment analysis and the spaCy library for text preprocessing. It reads a CSV file containing Amazon product reviews,
preprocesses the text data, and classifies the sentiment of each review based on the polarity score.

**It goes through the following steps:**

Data Preprocessing: Cleaning the dataset by removing null values and selecting the necessary columns.

Text Preprocessing: Tokenizing, lemmatizing, and removing stop words and punctuation from the reviews using spaCy.

Sentiment Analysis: Analyzing the polarity of each review using TextBlob to determine its sentiment.

Results: Calculating and displaying the percentages of positive, negative, and neutral sentiments in the dataset.

**Setup**
Before running the code, make sure you have the required Python libraries installed:

pip install numpy pandas spacy textblob
python -m spacy download en_core_web_md

Usage

Clone the repository:

git clone https://github.com/your-username/amazon-product-reviews-sentiment.git

Navigate to the project directory:

cd amazon-product-reviews-sentiment

Place your Amazon product reviews CSV file named amazon_product_reviews.csv in the project directory.

Run the Python script:

python sentiment_analysis.py

The application will preprocess the text data, analyze the sentiment of each review, and display the percentage of positive, negative, and neutral reviews.
