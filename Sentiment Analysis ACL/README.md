# Sentiment Analysis on IMDB ACL Dataset

This folder contains the implementation of sentiment analysis on the IMDB Large Movie Review Dataset (ACL dataset). The goal is to classify movie reviews into positive or negative sentiments using different word embedding techniques and logistic regression.

## Dataset Description

The IMDB Large Movie Review Dataset is widely used for sentiment classification tasks. It contains:
- **Training Data**: 25,000 labeled movie reviews.
- **Testing Data**: 25,000 labeled movie reviews.
- **Unlabeled Data**: Additional reviews without sentiment labels for unsupervised learning.

## Objective

The objective is to explore various word embedding techniques for sentiment analysis. This includes:
- **TF-IDF**
- **Word2Vec**
- **BERT**

## Results

The accuracy of sentiment classification:
- **TF-IDF**: 0.8866
- **Word2Vec**: 0.8686


## Tools Used

- **NLTK**: For text preprocessing and tokenization.
- **Gensim**: For Word2Vec embedding generation.
- **Hugging Face Transformers**: For BERT embeddings.
- **Scikit-Learn**: For Logistic Regression.

For more details on the dataset, please refer to the original [IMDB dataset page](https://ai.stanford.edu/~amaas/data/sentiment)
