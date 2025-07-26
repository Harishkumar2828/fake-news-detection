# Fake News Detection – Capstone Project

This is a Machine Learning Capstone Project developed using the "Fake and Real News Dataset" from Kaggle. The model detects whether a given news article is **fake** or **real** using NLP and TF-IDF techniques.

##  Objective
Build a classifier that can accurately distinguish between real and fake news articles using text data.

##  Dataset
- [Fake and Real News Dataset – Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
- Columns used: `title`, `text`, `label`

##  Methodology

- **Data Cleaning**
- **Label Encoding** (`FAKE` → 0, `REAL` → 1)
- **Text Preprocessing**: removing punctuation, lowercasing, stopwords
- **TF-IDF Vectorization**
- **Train/Test Split**
- **Model Used**: Logistic Regression

##  Results

- Accuracy: **98%**
- Precision, Recall, F1-score: ~0.98
- Confusion Matrix shows balanced predictions.

##  Model Evaluation

| Metric      | Value |
|-------------|-------|
| Accuracy    | 98%   |
| Precision   | 0.98  |
| Recall      | 0.98  |
| F1-Score    | 0.98  |

![Confusion Matrix](confusion_matrix.png)  <img width="501" height="422" alt="image" src="https://github.com/user-attachments/assets/ae9dc0bd-1e39-4145-87dc-431e07cf512b" />


##  Inference
The model performs exceptionally well and generalizes both classes (real/fake) equally.

##  Future Improvements
- Try more models: SVM, Random Forest, XGBoost
- Use LSTM/GRU models for deep learning approach
- Deploy using Flask or Streamlit

---

 **Submitted for CloudxLab Capstone Project**
 **Due Date**: July 26, 2025
 By: Harish Kumar
