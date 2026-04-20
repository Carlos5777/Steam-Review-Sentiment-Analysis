# Steam Review Sentiment Analysis (SVM)

## Overview
This project focuses on classifying Steam game reviews based on sentiment using a machine learning approach

The goal is to explore how text data can be transformed and used to detect whether a review is positive or negative, including cases with sarcasm or informal language

## Dataset
The dataset contains Steam user reviews with a corresponding recommendation label:
- 1 → Recommended (positive)
- 0 → Not recommended (negative)

## Approach
- Text preprocessing (lowercasing, removing null values)
- TF-IDF vectorization
- Machine Learning pipeline using:
  - TfidfVectorizer
  - LinearSVC

## Model
A pipeline was used to combine feature extraction and classification into a single workflow

## Evaluation
The model was evaluated using:
- Accuracy
- Classification report

## Results
The model achieved solid performance in classifying reviews and showed reasonable behavior even with informal or sarcastic inputs

## Example Predictions
Some test inputs were used to evaluate how the model handles sarcasm and informal expressions

## Tools and libraries
- Python
- pandas
- scikit-learn

## Files in this repository
- `svm_pipeline.ipynb`
- `svm_pipeline.py`
- `requirements.txt`

## Notes
This project reflects a more realistic NLP pipeline and demonstrates how machine learning models can be applied to user-generated content, I want to improve this same project in the future with a larger dataset and an even more powerful model. :D
