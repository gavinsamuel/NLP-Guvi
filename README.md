# NLP-Guvi
a compilation of projects done as part of assignment for Guvi's programme funded by the State Government


# NLP Projects Collection 📟

This repository contains five Natural Language Processing (NLP) projects, each designed to extract meaning or make predictions from unstructured text. All projects follow a common pipeline: text cleaning, tokenization, vectorization, and model training.

## Table of Contents

1. [Fake News Classification](#1-fake-news-classification)
2. [IMDb Movie Recommendation](#2-imdb-movie-recommendation)
3. [Topic Modelling - Indian Express](#3-topic-modelling---indian-express)
4. [MyECHO (BERT-based Model)](#4-myecho-bert-based-model)
5. [Sentiment Analysis](#5-sentiment-analysis)
6. [Common Pipeline](#common-nlp-pipeline)
7. [Installation](#installation)

---

## 1. Fake News Classification

This model classifies news articles as real or fake based on their content.

- **Dataset:** News articles labeled `real` or `fake`
- **Output:** Real/Fake classification

---

## 2. IMDb Movie Recommendation

A movie recommender system that analyzes plot summaries and suggests similar titles.

- **Dataset:** IMDb plots and metadata
- **Output:** List of similar movies based on input

---

## 3. Topic Modelling - Indian Express

Identifies underlying topics in Indian Express news articles.

- **Dataset:** News articles from Indian Express
- **Output:** Dominant topics per article

---

## 4. MyECHO (BERT-based Model)

MyECHO uses a fine-tuned BERT model to interpret and classify contextual user input. It excels in tasks where meaning depends heavily on sentence structure and nuance.

- **Dataset:** Custom contextual inputs
- **Model:** BERT
- **Output:** Classification or intent-based labels

---

## 5. Sentiment Analysis

Analyzes the sentiment of user input text, classifying it as positive, negative, or neutral.

- **Dataset:** Tweets, product reviews, or user comments
- **Output:** Sentiment label

---

## Common NLP Pipeline

All projects follow this industry standard workflow for NLP:

1. **Text Cleaning:**  
   - Lowercasing, punctuation/special character removal  
   - Stopwords removal and lemmatization

2. **Tokenization:**  
   - Word-level tokenization

3. **Vectorization:**  
   - Text-to-numerical representation (e.g., TF-IDF or Count Vectorizer)

4. **Model Training:**  
   - Trained using classical ML or custom logic (except MyECHO)

5. **Evaluation Metrics:**  
   - Accuracy, Precision, Recall, F1 Score

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/gavinsamuel/NLP-Guvi.git
cd NLP-Guvi


