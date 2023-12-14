# Resume-Classifier
# Resume Classifier

## Overview

This project is a simple resume classifier that helps categorize resumes into predefined job categories. The classification is done using a K-Nearest Neighbors (KNN) classifier trained on a dataset of resumes.

## Features

- **Data Exploration:** Explore the provided dataset to understand the distribution of resume categories using visualizations.
  
- **Text Cleaning:** Utilize the `cleanResume` function to preprocess resume text, removing unnecessary elements like URLs, mentions, and punctuations.

- **Word Cloud:** Generate a word cloud to visualize the most frequent words in the cleaned resume text using the `wordcloud` library.

- **Feature Extraction:** Use the `TfidfVectorizer` from scikit-learn to convert the cleaned text into numerical features suitable for machine learning.

- **Model Training:** Train a KNN classifier using the `OneVsRestClassifier` approach and evaluate its accuracy on training and test sets.

- **Making Predictions:** Allow users to input new resume text, and the model will predict its category, providing probability scores for each category.

- **Category Descriptions:** Provide brief descriptions of predicted categories based on the top predicted category.

## Prerequisites

Ensure you have the necessary libraries installed. You can install them using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn nltk wordcloud
