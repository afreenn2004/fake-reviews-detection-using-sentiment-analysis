# Fake Reviews Detection using BERT & Machine Learning

## 📌 Project Overview
This project detects fake product reviews using NLP and a BERT-based machine learning model. It includes a Flask web application for real-time predictions.

---

## ⚙️ Features
- Fake review classification using BERT
- NLP preprocessing and feature extraction
- Flask-based web interface
- Real-time prediction system

---
## 📸 UI Demonstration

The following screenshots show different scenarios of the fake review detection system.

---

### 🔹 Scenario 1: User inputs a clearly suspicious, overly positive review

<p align="center">
  <img src="Screenshots/Screenshot%202026-05-15%20165249.png" width="350"/>
</p>

<p align="center"><i>Web page after the review is inputted</i></p>

<p align="center">
  <img src="Screenshots/Screenshot%202026-05-15%20165449.png" width="350"/>
</p>

<p align="center"><i>BERT waterfall plot visualization</i></p>

<p align="center">
  <img src="Screenshots/Screenshot%202026-05-15%20165535.png" width="350"/>
</p>

<p align="center"><i>Metadata feature analysis bar plot</i></p>

---

### 🔹 Scenario 2: User inputs a detailed, balanced genuine review

<p align="center">
  <img src="Screenshots/Screenshot%202026-05-15%20165645.png" width="350"/>
</p>

<p align="center"><i>Web page after the review is inputted</i></p>

<p align="center">
  <img src="Screenshots/Screenshot%202026-05-15%20165738.png" width="350"/>
</p>

<p align="center"><i>BERT waterfall plot visualization</i></p>

<p align="center">
  <img src="Screenshots/Screenshot%202026-05-15%20165815.png" width="350"/>
</p>

<p align="center"><i>Metadata feature analysis bar plot</i></p>

---

### 🔹 Scenario 3: User inputs a short, vague review (potentially harder to classify)

<p align="center">
  <img src="Screenshots/Screenshot%202026-05-15%20165902.png" width="350"/>
</p>

<p align="center"><i>Web page after the review is inputted</i></p>

<p align="center">
  <img src="Screenshots/Screenshot%202026-05-15%20165944.png" width="350"/>
</p>

<p align="center"><i>BERT waterfall plot visualization</i></p>

<p align="center">
  <img src="Screenshots/Screenshot%202026-05-15%20170012.png" width="350"/>
</p>

<p align="center"><i>Metadata feature analysis bar plot</i></p>

---

## 🧠 Model Info
The model uses BERT for text classification with vectorization and scaling techniques.

Note: Model files are not included due to size limitations.

---

## 🛠️ Tech Stack
- Python
- PyTorch / Transformers
- Flask
- Scikit-learn
- HTML / CSS / JavaScript

---

## 📁 Project Structure
```
templates/
static/
notebook/
app.py
model_utils.py
requirements.txt
```

---

## 👩‍💻 Author
Afreen Ajaz
