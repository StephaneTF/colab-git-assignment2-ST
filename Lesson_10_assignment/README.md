# Assignment 10 – Sentiment Analysis

This project classifies Amazon Alexa reviews as positive or negative using Logistic Regression, SVM, and fine-tuned BERT.

The notebook covers text cleaning, Bag of Words, TF-IDF, Word2Vec embeddings, model tuning, and evaluation using accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices, and ROC curves.

## Running the Notebook

Open the notebook in Google Colab, select a GPU runtime for faster BERT training, upload `amazon_alexa.tsv`, run the dependency installation cells, and execute the remaining cells in order.

Mount Google Drive before BERT training to save checkpoints, and let training finish before running BERT predictions and evaluation.
