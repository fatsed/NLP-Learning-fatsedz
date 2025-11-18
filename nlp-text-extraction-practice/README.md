# 🧠 NLP Text Extraction Practice

This folder contains a collection of Jupyter notebooks designed to help you learn and practice different text extraction techniques in Natural Language Processing (NLP).  
The exercises progress from simple text fetching to web scraping and API communication.

---

## 📘 Notebooks Overview

### **1️⃣ 01_text_url.ipynb**  
**Summary:** Fetching text from a remote `.txt` file using an HTTP GET request.  
**Description:**  
Demonstrates how to load text from a URL using the `requests` library and process or save the downloaded content.

---

### **2️⃣ 02_web_scrapping.ipynb**  
**Summary:** Basic HTML scraping with `urllib` and `BeautifulSoup`.  
**Description:**  
Shows how to retrieve a webpage, parse HTML tags, extract headings and paragraph text, and combine them into clean output.

---

### **3️⃣ 03_api_request_urllib3.ipynb**  
**Summary:** Sending API requests using the `urllib3` library.  
**Description:**  
Covers making HTTP GET requests with custom headers and reading API responses.

---

### **4️⃣ 04_api_error_handling.ipynb**  
**Summary:** Handling common API request errors.  
**Description:**  
Explains how to detect status codes such as `429 Too Many Requests`, use `Retry-After`, and safely retry failed requests.

---

### **5️⃣ 05_api_with_params.ipynb**  
**Summary:** Sending API requests with query parameters.  
**Description:**  
Demonstrates how to pass key–value parameters using the `params` argument in `requests.get()`. Includes an example using the Universities API.

---

### **6️⃣ wordcloud.ipynb**  
**Summary:** Creating a word cloud from text.  
**Description:**  
Uses the `wordcloud` and `matplotlib` libraries to visualize the most frequent words in a text.

---

## 🛠 Required Libraries
pip install requests
pip install beautifulsoup4
pip install urllib3
pip install wordcloud
pip install matplotlib


---

## 🚀 How to Use

1. Open the notebooks in Jupyter Notebook, JupyterLab, or Google Colab.  
2. Run the cells step by step to follow each text extraction technique.

---

## 🙌 Author  
fatsedz — Learning NLP with Python
