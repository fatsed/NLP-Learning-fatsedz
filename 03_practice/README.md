# 🧠 03 – NLP Practice Exercises

This folder contains integrated NLP exercises that combine everything learned in the previous sections, including **text extraction**, **cleaning**, **tokenization**, **POS tagging**, **NER**, **frequency analysis**, and **semantic similarity**.

Each notebook focuses on a different part of the NLP pipeline, giving you hands-on practice in real-world scenarios.

---

## 📌 1) 01_news_nlp_pipeline.ipynb

A complete mini-pipeline for processing **technology news**:

### 🔹 Features:
- Scrape headlines and summaries from a news website  
- Clean and normalize extracted text  
- Tokenization + stopword removal  
- POS tagging  
- Named Entity Recognition (NER)  
- Extract:
  - Most frequent **NOUN** tokens  
  - Most frequent **PERSON** entities  

### 🎯 Goal:
Learn how to build an **end-to-end NLP workflow** starting from raw online text.

---

## 📌 2) 02_top_words_similarity_gensim.ipynb

Explore **word frequency** and **semantic similarity** using **gensim**.

### 🔹 Features:
- Load a text file or custom corpus  
- Compute top frequent words  
- Train a simple **Word2Vec** or **FastText** model  
- Calculate word similarity  
- List the most similar words to a given input  

### 🎯 Goal:
Understand how word embeddings represent semantic meaning and how similarity is computed.

---

## 📌 3) 03_persian_preprocess_ner_freq.ipynb

Full preprocessing + NER pipeline for **Persian text** using **Hazm** and **Stanza**.

### 🔹 Features:
- Input: Persian text (manual entry, file, or fetched from URL)  
- Preprocessing:
  - Normalize  
  - Tokenize  
  - Remove stopwords  
  - Clean digits, punctuation, and Latin letters  
  - Optional: stemming/lemmatization  
- Named Entity Recognition (NER) for Persian  
- Extract:
  - PERSON entities  
  - ORGANIZATION entities  
- Compare frequency **before vs. after preprocessing**  
- Print top 10 frequent persons and organizations  

### 🎯 Goal:
Learn how Persian NLP differs from English and how to evaluate preprocessing impact on NER accuracy.

---

## 📁 Folder Purpose

This set of exercises is designed to give students (Groups 2–4) hands-on practice with the most important NLP tasks:

- Text extraction  
- Cleaning & normalization  
- Tokenization  
- POS tagging  
- Named Entity Recognition  
- Frequency analysis  
- Word embeddings & similarity  

Each notebook can be used independently or integrated as part of a larger NLP project.

---

✳️ *Feel free to modify, extend, or add new notebooks as your NLP skills grow!*
