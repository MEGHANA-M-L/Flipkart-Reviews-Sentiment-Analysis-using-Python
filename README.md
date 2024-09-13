# Flipkart Review Sentiment Analysis - A Machine Learning Project

This machine learning project aims to classify customer reviews on Flipkart as positive or negative by analyzing the text of the reviews. It leverages natural language processing (NLP) for text preprocessing and trains a classification model using a Decision Tree.

## Project Overview

- **Objective**: To build a machine learning model that predicts whether a product review is positive or negative based on customer feedback and ratings.
- **Data Source**: The data is sourced from a CSV file (`flipkart_data.csv`) containing reviews and ratings.
- **Model**: A `DecisionTreeClassifier` from `scikit-learn` is used for classification.
- **NLP Techniques**: The text is preprocessed using tokenization, stopword removal, and vectorization with TF-IDF.

## Dependencies

To run this project, you'll need the following Python packages:

- `pandas`
- `seaborn`
- `matplotlib`
- `nltk`
- `wordcloud`
- `tqdm`
- `scikit-learn`

You can install these using the command:
```bash
pip install pandas seaborn matplotlib nltk wordcloud tqdm scikit-learn
