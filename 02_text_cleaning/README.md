# 🧹 NLP Text Cleaning & Preprocessing Practice

This folder contains a series of Jupyter notebooks designed to practice fundamental text preprocessing and basic NLP techniques in both **English** and **Persian**.  
The exercises start from simple text cleaning and gradually build up to full mini–pipelines with vectorization.

---

## 📂 Notebooks Overview

### 1️⃣ `01_basic_cleaning.ipynb`  
**Topic:** Basic text cleaning  
**Highlights:**  
- Load raw text from a `.txt` file  
- Remove punctuation, newlines, digits  
- Normalize whitespace and produce a cleaned text string  

---

### 2️⃣ `02_tokenize_stopwords.ipynb`  
**Topic:** Tokenization & stopword removal (English)  
**Highlights:**  
- Sentence and word tokenization (NLTK)  
- English stopwords with `nltk.corpus.stopwords`  
- Compare tokens before and after stopword filtering  

---

### 3️⃣ `03_stem_lemma.ipynb`  
**Topic:** Stemming vs lemmatization  
**Highlights:**  
- Porter & Snowball stemmers  
- WordNet lemmatizer  
- Side–by–side comparison of `original | stem | lemma`  

---

### 4️⃣ `04_ngrams_pos_ner.ipynb`  
**Topic:** N-grams, POS tagging and (English) NER  
**Highlights:**  
- Unigrams, bigrams, trigrams with NLTK  
- POS tagging and short explanation of POS tags  
- (Optional) Named Entity Recognition using `ne_chunk`  

---

### 5️⃣ `05_vectorization.ipynb`  
**Topic:** Text vectorization  
**Highlights:**  
- Bag-of-words with scikit-learn `CountVectorizer`  
- Keras `Tokenizer` and count matrix  
- Compare vocabulary and matrix shape across methods  

---

### 6️⃣ `06_final_practice_en.ipynb`  
**Topic:** Final English pipeline  
**Highlights:**  
- End-to-end English text pipeline:
  cleaning → tokenization → stopwords → stem/lemma → n-grams → POS/NER → vectorization  
- Small analysis questions at the end  

---

### 7️⃣ `07_final_practice_fa.ipynb`  
**Topic:** Final Persian pipeline (web text)  
**Highlights:**  
- Fetch a Persian article (e.g., from Wikipedia) with `requests` + `BeautifulSoup`  
- Normalize & clean text using Hazm  
- Persian tokenization and stopword removal  
- Stemming & lemmatization in Hazm  
- Persian n-gram analysis  
- Vectorization with `CountVectorizer` (custom Hazm tokenizer) and Keras `Tokenizer`  

---

## ⚙️ Requirements

Main Python packages used in these notebooks:

- `nltk`
- `scikit-learn`
- `tensorflow` / `keras`
- `hazm`
- `requests`
- `beautifulsoup4`
- `gensim` (optional, depending on your environment)
- `fasttext`, `flashtext` (optional, some installs)

NLTK resources (run once in a separate cell):

```python
import nltk
nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
nltk.download('averaged_perceptron_tagger_eng')
nltk.download('maxent_ne_chunker')
nltk.download('maxent_ne_chunker_tab')
nltk.download('words')
```
For Persian processing, install Hazm (no deps):
```
!pip install hazm --no-deps
```
🚀 Suggested Order of Study

Start with 01_basic_cleaning.ipynb and 02_tokenize_stopwords.ipynb
Continue with 03_stem_lemma.ipynb
Move to 04_ngrams_pos_ner.ipynb and 05_vectorization.ipynb
Finish with the two final practice notebooks:
06_final_practice_en.ipynb (English)
07_final_practice_fa.ipynb (Persian)
