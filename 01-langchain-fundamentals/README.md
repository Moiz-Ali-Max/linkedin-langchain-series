# 📘 LangChain Lecture 01 — Document & Data Loaders

This folder contains code examples on **LangChain Document/Data Loaders**.  
The goal is to understand how we can load data from different sources into LangChain.

---
### Installation Guide
 conda create -n environment-name python=3.11 
 conda activate environment-name 

 pip install --upgrade "langchain>=0.3,<0.4"
 pip install --upgrade "langchain-community>=0.3,<0.4" 
 pip install --upgrade "langchain-text-splitters>=0.3,<0.4" 
 pip install --upgrade "langchain-core>=0.3,<0.4" 
 pip install google-generativeai ```

 pip install pypdf 
 pip install bs4 
 pip install unstructured 
pip install markdown 

---

---

## 🔎 What are Document Loaders?
Document loaders are **helpers** in LangChain that bring data from files, webpages, APIs, or databases into a format the LLM can work with.  

Think of them like **import tools**:
- PDF Loader → read PDF files
- Web Loader → fetch webpage content
- CSV Loader → read rows from spreadsheets
- Markdown / HTML / JSON Loaders → structured text files
- Directory Loader → multiple files at once
- Microsoft Office Loaders → Word, PowerPoint, Excel
- Custom Loader → build your own from any source

---

---

## 📄 Notes
Detailed notes are available here:  
👉 [Day1-LangChain.pdf](./day1-langchain.pdf)

---

