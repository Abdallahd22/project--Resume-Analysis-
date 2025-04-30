# 📄 Resume Analyzer Web App (Flask + Pyngrok on Google Colab)

This project is a lightweight **Resume Analyzer** built using Python, Flask, and scikit-learn. It allows users to upload resumes in PDF or DOCX formats and analyzes them to extract useful information such as **name**, **email**, **phone number**, **skills**, and **major**, and suggests the best-fitting job role based on cosine similarity matching.

It is designed to run in **Google Colab** and exposes the local Flask server using **ngrok**.

---

## 🚀 Features

- 📄 Upload and parse resumes (`.pdf` or `.docx`)
- 🔍 Extract:
  - Name
  - Email
  - Phone Number
  - Skills
  - Major
- 🧠 Match skills to job profiles (e.g., Data Scientist,Web Developer, DevOps)
- 📊 Displays job match score histogram
- 🔐 Runs securely on Flask using ngrok (auto port tunneling in Colab)
- 🖥️ Simple HTML-based frontend using Flask template strings

---

## 🧰 Technologies Used

- Python 3 (Google Colab)
- Flask
- Pyngrok
- scikit-learn
- PyPDF2 / python-docx
- HTML/CSS (template string)
- Matplotlib
- accuracy
- Plot bar

## 📦 Installation

In Google Colab:

```python
!pip install flask pyngrok python-docx PyPDF2 flask-cors matplotlib

