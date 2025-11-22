# 🧩 03 — Vectorization  
This folder contains all fundamental methods for converting text into numerical
representations. Vectorization is the core step in every NLP pipeline, and here
we explore techniques ranging from simple word encodings (One-Hot) to more
advanced feature extraction methods (TF–IDF).

---

## 📂 Notebook Overview

### 1️⃣ **01_one_hot_encoding.ipynb**
This notebook covers:
- Creating a vocabulary from text  
- Converting tokens into One-Hot vectors  
- Limitations of One-Hot (sparse vectors, no semantic meaning)

**Good for:** building basic intuition on how text becomes numbers.

---

### 2️⃣ **02_bow_countvectorizer.ipynb**
In this notebook you will learn:
- How Bag of Words (BoW) works  
- Building a Document–Term Matrix  
- Using `CountVectorizer` from scikit-learn  
- Visualizing the matrix with pandas DataFrame  

**Pros:** simple and fast  
**Cons:** ignores word meaning and order.

---

### 3️⃣ **03_tfidf_vectorizer.ipynb**
This notebook introduces:
- The concept of Term Frequency (TF) and Inverse Document Frequency (IDF)  
- How TF–IDF reduces the importance of common words  
- Generating TF–IDF vectors using `TfidfVectorizer`  
- Identifying the most important terms in a document  

TF–IDF usually outperforms BoW in most text-classification tasks.

---

### 4️⃣ **04_compare_bow_tfidf.ipynb**
This notebook provides a practical comparison of BoW vs TF–IDF:
- A small sentiment dataset (positive/negative sentences)  
- Training a Naive Bayes classifier using:
  - Bag of Words  
  - TF–IDF  
- Comparing accuracy and behavior of both models  

Great for understanding how vectorization impacts model performance.

---

### 5️⃣ **05_brown_corpus_practice.ipynb**
This is the main practice notebook of this folder.

It includes:
- Downloading the **Brown Corpus** from Kaggle  
- Extracting two categories:
  - `cf` → humor  
  - `cs` → science_fiction  
- Text preprocessing with spaCy:
  - Tokenization  
  - Lemmatization  
  - Removing stopwords & punctuation  
- TF–IDF vectorization  
- Training a Naive Bayes classifier  
- Detailed evaluation using `classification_report`

This notebook demonstrates a **complete NLP pipeline** from raw text to model evaluation.

---

## 🚀 How to Run the Notebooks
All notebooks are tested in **Google Colab**.

1. Open the notebook in Colab  
2. Run the cells from top to bottom  
3. If a notebook requires Kaggle datasets, upload your `kaggle.json`  
4. Install dependencies when prompted  

---

## 📦 Requirements

```bash
pip install scikit-learn
pip install spacy
pip install kaggle
python -m spacy download en_core_web_sm
