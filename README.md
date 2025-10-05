# Sentiment Analysis on IMDB Reviews

## Overview
This project performs sentiment analysis using the IMDB dataset. The goal is to classify movie reviews as **positive** or **negative** based on their text content. The project explores two machine learning approaches:

1. **Logistic Regression**  
2. **LSTM (Long Short-Term Memory) Neural Networks**

---

## Dataset
The dataset consists of **50,000 IMDB movie reviews** labeled as positive or negative, with a balanced split of 25,000 reviews for training and 25,000 for testing. Each review contains:

- **Review:** The text content of the movie review  
- **Sentiment:** Label of the review (1 = positive, 0 = negative)  

Here is the link to the dataset: [IMDB Reviews Dataset on Kaggle](https://www.aclweb.org/anthology/P11-1015/](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) 
---

## Exploratory Data Analysis (EDA)
- Checked class distribution (positive vs negative)  
- Examined review length distribution  
- Generated word clouds for positive and negative reviews  
- Extracted top bigrams for each sentiment  

---

## Data Preprocessing
- Checked for missing values and removed duplicates  
- Lowercased text, removed HTML tags, URLs, and stop words  
- Encoded sentiment labels (1 = positive, 0 = negative)  

**Model-specific preprocessing:**  
- **Logistic Regression:** TF-IDF vectorization, top 5,000 words, 80/20 train-test split  
- **LSTM:** Tokenized text, padded sequences to 200 tokens, 80/20 train-test split with stratification  

---

## Models
We built and trained two types of models:

- **Logistic Regression** for traditional machine learning text classification  
- **LSTM Neural Networks** to capture sequential patterns in text data  


## Collaborators
- Eddy Gasana
- Placide Imanzi Kabisa
- Jean Paul Irakoze
