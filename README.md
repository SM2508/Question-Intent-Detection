# Question-Intent-Detection
 DUPLICATE QUESTION DETECTION USING NLP AND DEEP LEARNING TECHNIQUES
 
## Project Overview

This project focuses on Duplicate Question Detection, a common Natural Language Processing (NLP) task used in question-answering platforms such as Quora. The goal is to determine whether two questions have the same meaning, even if they are written differently.
The project compares multiple text representation and deep learning approaches for identifying duplicate questions and evaluates their performance on a labeled dataset.

## Dataset

The dataset contains pairs of questions along with a target label:

| Column       | Description                                     |
| ------------ | ----------------------------------------------- |
| question1    | First question                                  |
| question2    | Second question                                 |
| is_duplicate | Target label (1 = Duplicate, 0 = Non-Duplicate) |

### Example

| Question 1           | Question 2                       | Label |
| -------------------- | -------------------------------- | ----- |
| What is AI?          | What is Artificial Intelligence? | 1     |
| How to learn Python? | What is the capital of France?   | 0     |


## Methodology

1. Clean and preprocess textual question data.
2. Identify and remove noisy or invalid records.
3. Convert text into numerical representations.
4. Train and evaluate different machine learning and deep learning models.
5. Compare the effectiveness of traditional NLP and neural network approaches for semantic similarity detection.

## Data Preprocessing

The following preprocessing steps were applied:

- Removal of HTML tags
- Removal of special characters and punctuation
- Lowercasing text
- Whitespace normalization
- Dataset cleaning and validation
- Identification and removal of invalid labels
- Train-test splitting

## Models Implemented

1. TF-IDF + Logistic Regression
2. Word2Vec Embeddings
3. Siamese LSTM Network
4. Sentence Transformers

## Technologies Used

Python
Pandas
NumPy
Scikit-Learn
TensorFlow / Keras
Gensim
Sentence Transformers
Matplotlib

## Key Learnings

- Traditional NLP methods provide strong baseline performance.
- Word embeddings capture semantic relationships better than bag-of-words techniques.
- Siamese Networks are effective for sentence-pair similarity tasks.
- Transformer-based models achieve superior semantic understanding and often outperform traditional approaches.

