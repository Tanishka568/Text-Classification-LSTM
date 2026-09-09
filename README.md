# 🧠 Text Classification using Embedding Layer and LSTM Network

## 📌 Project Information

**Course:** Generative AI  
**Lab Assignment:** Text Classification using Embedding Layer and LSTM Network  
**Student Name:** Tanishka Vishnu Tapkir  
**PRN Number:** 202401110071  
**Batch:** A3  

---

## 🎯 Objective

The objective of this project is to build a text classification model using an **Embedding Layer** and an **LSTM (Long Short-Term Memory) Network**.

The model is trained to classify movie reviews into two categories:

- Positive Review
- Negative Review

The performance of the model is evaluated using appropriate classification metrics.

---

## 📖 Introduction

Text Classification is an important task in Natural Language Processing (NLP). It involves automatically classifying text into predefined categories.

In this project, a deep learning model is developed using an **Embedding Layer** and an **LSTM Network** for sentiment classification.

The Embedding Layer converts words into numerical vector representations, while the LSTM Network learns patterns and relationships from sequences of words.

---

## 📊 Dataset

The **IMDB Movie Reviews Dataset** is used for this project.

The dataset is available directly through the **TensorFlow/Keras library**.

Each movie review is classified into one of two categories:

| Label | Sentiment |
|------|-----------|
| 0 | Negative |
| 1 | Positive |

The dataset is divided into:

- Training Dataset
- Testing Dataset

---

## ⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 🧠 Model Architecture

The deep learning model consists of the following layers:

```text
Input Text
    │
    ▼
Text Preprocessing and Padding
    │
    ▼
Embedding Layer
    │
    ▼
LSTM Layer
    │
    ▼
Dense Layer
    │
    ▼
Dropout Layer
    │
    ▼
Output Layer (Sigmoid)
    │
    ▼
Positive / Negative Prediction
