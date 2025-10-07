# 📧 Spam Classifier using NLP and Machine Learning

This project is a **Spam Classifier** built using **Natural Language Processing (NLP)** and **Machine Learning** techniques.  
It identifies whether a given message (SMS or email) is **spam** or **ham (not spam)** based on text analysis.

---

## 🚀 Overview

Spam detection is one of the most common NLP applications.  
In this project, we:
- Preprocess text data using NLP techniques  
- Extract features using **Bag of Words (BoW)** or **TF-IDF Vectorization**  
- Train a **Machine Learning model** (e.g., Naive Bayes)  
- Evaluate model accuracy using test data  

---

## 🧠 Tech Stack

- **Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, NLTK
- **Algorithm:** Naive Bayes 
- **Environment:** Jupyter Notebook (`.ipynb`)

---

## 📊 Dataset

Dataset used: **SMS Spam Collection Dataset**  
- Contains ~5,000 labeled SMS messages  
- Two categories:  
  - `ham` → Non-spam messages  
  - `spam` → Unwanted promotional or fraudulent messages  

If you don’t have the dataset, you can download it from:  
[📂 Kaggle - SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

## ⚙️ Workflow

1. **Import Libraries**  
2. **Load Dataset**  
3. **Data Cleaning & Preprocessing**  
   - Removing punctuation, numbers, and stopwords  
   - Tokenization and Lemmatization  
4. **Feature Extraction** using TF-IDF Vectorizer  
5. **Model Training** using Naive Bayes  
6. **Evaluation** using Accuracy and Confusion Matrix  
7. **Prediction** on custom input messages  

---

## 📈 Results

- Achieved high accuracy on test data (typically 95–98%)  
- Effective in detecting spam vs. ham messages  
- Visualized confusion matrix and performance metrics  

---

## ▶️ How to Run

1. Clone this repository  
   ```bash
   git clone https://github.com/Vivek20oct/spam_classifier_NLP.git
