Multi-class customer intent classification using NLP and machine learning
# Customer Intent Detection using Natural Language Processing
Multi-class customer intent classification using NLP and machine learning


## Problem Statement
The objective of this project is to classify customer messages into different intent categories such as refund requests, order management, delivery queries, payment issues, and account-related concerns.

## Dataset
- Source: Kaggle (Bitext Customer Support Dataset)
- The dataset contains customer queries labeled with fine-grained intent classes.
- Similar intents were merged into business-level categories for better interpretability.

## Approach
- Text preprocessing: lowercasing, stopword removal, lemmatization
- Feature extraction using TF-IDF with unigrams and bigrams
- Multi-class intent classification using Logistic Regression

## Evaluation
- Train-test split with stratified sampling
- Model evaluated using confusion matrix and classification report
- Minimal confusion observed between semantically similar intents

## Key Insights
- Strong overall intent classification performance
- Errors mainly occur between closely related intents
- Suitable for real-world customer support automation

## Technologies Used
Python, Pandas, NLTK, Scikit-learn, Matplotlib, Seaborn

## Conclusion

This project demonstrates an end-to-end NLP pipeline for multi-class customer intent detection.
The model shows strong performance with minimal confusion between semantically similar intents,
making it suitable for real-world customer support automation and ticket routing systems.

