# Customer Sentiment Analysis

## Overview

This project builds and evaluates a Natural Language Processing (NLP) model that classifies customer reviews as either positive or negative. Reviews from IMDb, Amazon, and Yelp were combined into a single dataset and processed using text preprocessing, tokenization, and an LSTM neural network.

---

## Business Problem

Organizations receive thousands of customer reviews across multiple platforms. Manually reviewing customer feedback is time-consuming and inconsistent. This project demonstrates how machine learning can automatically classify customer sentiment to help organizations monitor customer satisfaction and identify trends.

---

## Tools Used

- Python
- Pandas
- TensorFlow / Keras
- NLTK
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

- Combined IMDb, Amazon, and Yelp review datasets
- Cleaned and normalized review text
- Removed stop words, punctuation, duplicate reviews, and unusual characters
- Lemmatized text using NLTK
- Tokenized reviews into numerical sequences
- Applied sequence padding
- Built and trained an LSTM-based sentiment classification model
- Tuned model architecture to reduce overfitting
- Evaluated performance using accuracy, precision, recall, specificity, and a confusion matrix

---

## Model Performance

Final model performance on the test dataset:

- Accuracy: 79.44%
- Precision: 76.92%
- Recall: 83.92%
- Specificity: 75.00%

The final model reduced trainable parameters by approximately 73% while maintaining comparable predictive performance.

---

## Key Findings

- Text preprocessing significantly reduced vocabulary size and improved model consistency.
- Early stopping helped prevent overfitting.
- Reducing model complexity improved generalization.
- The model correctly classified approximately 8 out of every 10 unseen reviews.

---

## Repository Structure

```
customer-sentiment-analysis
│
├── Customer_Sentiment_Analysis.ipynb
├── Project_Report_Customer_Sentiment_Analysis.pdf
├── cleaned_full_data.csv
├── trained_sentiment_model.keras
├── confusion_matrix.png
├── accuracy_curve.png
├── loss_curve.png
└── README.md
```

---

## Skills Demonstrated

- Natural Language Processing (NLP)
- Text Preprocessing
- Sentiment Analysis
- TensorFlow
- Keras
- LSTM
- Machine Learning
- Model Evaluation
- Python
- Data Cleaning
