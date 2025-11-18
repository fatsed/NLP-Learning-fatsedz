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
Explains how to detect status codes such as `429 Too Many Requests`, use the `Retry-After` header, and safely retry failed requests.

---

### **5️⃣ 05_api_with_params.ipynb**  
**Summary:** Sending API requests with query parameters.  
**Description:**  
Demonstrates how to pass key–value parameters using the `params` argument in `requests.get()`. Includes an example using the Universities API.

---

### **6️⃣ 06_api_with_params_universities.ipynb**  
**Summary:** API request with query parameters using the Universities API.  
**Description:**  
This notebook demonstrates how to send an HTTP GET request with parameters using the `requests` library.  
It sends a search query to the Universities API with filters for country and name, prints the final resolved URL, and displays the number of matching universities returned by the API.

---

### **7️⃣ 07_uci_student_performance_download.ipynb**  
**Summary:** Downloading datasets from the UCI Machine Learning Repository.  
**Description:**  
Demonstrates how to download a ZIP dataset directly from the UCI repository using `urllib.request`.  
Retrieves the "Student Performance" dataset and saves it locally for further processing.

---

### **8️⃣ 08_kaggle_api_mobile_reviews.ipynb**  
**Summary:** Introduction to downloading datasets using the Kaggle API.  
**Description:**  
Shows the initial setup required to use the Kaggle API for dataset downloads, focusing on mobile review datasets.

---

## 🛠 Required Libraries

```bash
pip install requests
pip install beautifulsoup4
pip install urllib3
pip install wordcloud
pip install matplotlib


🚀 How to Use

Open the notebooks in Jupyter Notebook, JupyterLab, or Google Colab.

Run the cells step by step to follow each text extraction technique.

🙌 Author

fatsedz — Learning NLP with Python
