# NLP Practice: Stemming and Lemmatization

This repository contains practical implementations of fundamental Natural Language Processing (NLP) techniques. These exercises were completed as part of the **HEC Generative AI Training Program (Cohort 3)** during the first week's practice sessions.

## 🚀 Project Overview
The goal of this project is to demonstrate the difference between two key text normalization techniques:
1. **Stemming:** A rule-based process that chops off the ends of words to find the root form (often resulting in non-dictionary words).
2. **Lemmatization:** A more sophisticated process that uses a dictionary (WordNet) and Part-of-Speech (POS) tagging to find the accurate base form (Lemma) of a word.

## 🛠️ Tools & Libraries Used
* **Python 3.x**
* **NLTK (Natural Language Toolkit):** Used for tokenization, stemming, and lemmatization.
* **Google Colab:** The environment used for development.

## 📋 Key Steps Implemented
* **Tokenization:** Breaking down raw text into individual words or tokens.
* **Stemming:** Using the `PorterStemmer` to reduce words to their stems.
* **POS Tagging:** Assigning grammatical tags (Noun, Verb, etc.) to each token to improve lemmatization accuracy.
* **Lemmatization:** Using `WordNetLemmatizer` combined with a helper function to accurately normalize text.

## 💻 How to Run
To run this notebook, ensure you have NLTK installed and download the following resources within your environment:
```python
import nltk
nltk.download('punkt_tab')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger_eng')
