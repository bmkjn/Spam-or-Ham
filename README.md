# Spam-or-Ham
Overview
This repository contains an email classification system designed to classify emails as either "spam" or "ham" (non-spam). The classification is based on natural language processing (NLP) techniques and a Naive Bayes classifier. The process involves cleaning the text documents by removing punctuation, numbers, and stopwords, converting the text to lowercase, and applying stemming. Following text preprocessing, both CountVectorizer and TF-IDF Vectorizer are employed to create bag-of-words representations. Finally, a Naive Bayes Gaussian model is trained to classify emails based on their textual content.

Workflow
Text Preprocessing:
Removal of punctuation, numbers, and stopwords.
Conversion of text to lowercase.
Application of stemming to reduce words to their root forms.
Feature Extraction:
Utilization of both CountVectorizer and TF-IDF Vectorizer to create bag-of-words representations.
Model Training:
Implementation of a Naive Bayes Gaussian model using scikit-learn.
Evaluation:
Comparison of predicted outputs with original labels to assess the performance of the classifier.

Requirements
Python 3.x
NumPy
Pandas
NLTK
scikit-learn

Results
The performance metrics of the classifier, including accuracy, precision, recall, and F1-score, can be found in the output logs. Additionally, visualizations may be provided to illustrate the classification results and model performance.

Contributions
Contributions are welcome! If you find any bugs or have suggestions for improvement, feel free to open an issue or submit a pull request.
