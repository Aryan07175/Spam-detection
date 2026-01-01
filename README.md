# 📧 Spam Mail Detection Web App

A **machine learning–powered web application** that detects whether an email is **Spam** or **Not Spam**.  
The project evaluates multiple ML classification models and deploys the **best-performing model (Naive Bayes)** using a Flask-based web interface for real-time predictions.


## 🚀 Features

- Implemented and evaluated **five classification models**:
  - ✅ **Naive Bayes** (Best performing)
  - Support Vector Machine (SVM)
  - Random Forest
  - Logistic Regression
  - K-Nearest Neighbors (KNN)

- Compared model performance using **accuracy metrics**
- Selected **Naive Bayes** as the final model
- Saved trained model as `model.pkl`
- Built an **interactive Flask web app** for live spam detection
- Simple and user-friendly UI

---

## 📊 Model Accuracy Comparison

| Model                  | Accuracy |
|------------------------|----------|
| ✅ Naive Bayes          | **97.14%** |
| Logistic Regression   | 96.67% |
| SVM                   | 96.19% |
| Random Forest         | 94.76% |
| K-Nearest Neighbors   | 77.62% |

➡️ **Naive Bayes** was chosen as the final model based on highest accuracy.

---

## 🛠 Tech Stack

### Backend
- Python
- Flask

### Machine Learning Libraries
- scikit-learn
- pandas
- numpy
- joblib

### Frontend
- HTML
- CSS  
(using Flask `templates` and `static` folders)


