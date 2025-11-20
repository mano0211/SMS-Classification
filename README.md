# 📧 Email & SMS Spam Classifier using NLP + Machine Learning  
A complete end-to-end spam detection system built using **Natural Language Processing (NLP)** and **Supervised Machine Learning**.  
This project can classify **email text** or **SMS messages** as either **spam** or **ham (not spam)** using TF-IDF features and multiple ML models (Naive Bayes, Logistic Regression, SVM).

![Spam Detection](https://via.placeholder.com/900x250?text=Email+%2F+SMS+Spam+Classifier)

---

## 🚀 Features
- End-to-end NLP pipeline  
- Text cleaning & preprocessing  
- TF-IDF feature extraction (word & character n-grams)  
- Multiple ML models:
  - Multinomial Naive Bayes  
  - Logistic Regression  
  - Logistic Regression with Hyperparameter Tuning  
  - Linear SVM with Probability Calibration  
- Model selection using validation metrics  
- Graphs:
  - ROC Curves  
  - F1-Score Comparison  
  - Accuracy/Precision/Recall/F1 Bar Charts  
- Interactive classifier (ipywidgets in Colab)  
- REST-style API using **FastAPI TestClient**  
- Exportable final trained model (`joblib`)  
- Ready for deployment (FastAPI + Uvicorn outside Colab)

---

## 📁 Project Structure

