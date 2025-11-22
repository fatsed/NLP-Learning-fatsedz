# 🔷 Similarity & Distance in NLP  
This folder contains a complete set of notebooks demonstrating different similarity and distance metrics used in Natural Language Processing (NLP), including string similarity, word similarity using Word2Vec, sentence similarity, and visualization techniques.

These notebooks are designed for both learning and practical implementation.

---

## 📁 Contents

### **1️⃣ Word Similarity (Word2Vec)**
- Training a Persian Word2Vec model using Gensim  
- Computing similarity between word vectors  
- Cosine similarity  
- Euclidean distance  
- Manhattan distance  
- Visualization of word distances using t-SNE (with correct Persian rendering)

Notebook:  
`04_similarity_distance.ipynb`

---

## 📌 Key Concepts Covered

### **✔ Cosine Similarity**
Measures the angle between two vectors:
\[
\text{cosine}(a,b) = \frac{a \cdot b}{\|a\| \|b\|}
\]

Used to find semantic similarity between words and sentences.

---

### **✔ Euclidean Distance**
Direct geometric distance between vectors:
\[
d(a,b) = \|a - b\|
\]

---

### **✔ Manhattan Distance**
Sum of absolute differences between two vectors.

---

### **✔ Levenshtein Distance (Edit Distance)**
The minimum number of insertions, deletions, or substitutions required to transform one word into another.

Examples:
- "کتاب" ↔ "کباب"
- "سلام" ↔ "سالم"

---

### **✔ Fuzzy String Matching**
Using `fuzzywuzzy` to compute similarity between noisy or misspelled strings.

---

### **✔ Jaccard Similarity**
Used to compare sets of tokens:
\[
J(A,B) = \frac{|A \cap B|}{|A \cup B|}
\]
Great for measuring similarity between short text or sentences.

---

### **✔ Sentence Similarity (Embedding-Based)**
Each sentence is converted into a vector by averaging its word embeddings.  
Then cosine similarity is used to measure semantic closeness.

Included:
- Heatmap of sentence similarity matrix
- Color visualization using seaborn

---

### **✔ t-SNE Visualization**
A 2-D visualization of word embeddings for understanding semantic clusters.  
Supports **Persian text** using:
- `arabic_reshaper`
- `python-bidi`
- `DejaVu Sans` font  

Output: scatter plot of semantic word groups.

---

## 🧠 Requirements

These notebooks use:
- `gensim`
- `hazm`
- `numpy`
- `scikit-learn`
- `seaborn`
- `matplotlib`
- `python-Levenshtein`
- `fuzzywuzzy`
- `arabic-reshaper`
- `python-bidi`

All dependencies can be installed with:

```bash
pip install gensim hazm python-Levenshtein fuzzywuzzy arabic-reshaper python-bidi seaborn
