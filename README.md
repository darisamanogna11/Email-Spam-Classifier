# 📧 Email Spam Classifier using Machine Learning

This project is a binary classification model that detects whether an email is **spam** or **not spam (ham)** using Natural Language Processing (NLP) techniques and a supervised machine learning algorithm.

---

## 🧠 Project Overview

The goal is to classify email messages into:
- **Spam (0)** – unwanted/malicious messages
- **Ham (1)** – legitimate messages

The project uses:
- Text preprocessing
- TF-IDF vectorization
- Logistic Regression classifier

---

## 📂 Dataset

- **File:** `mail_data.csv`
- **Columns:**
  - `Category`: Email label (`spam` or `ham`)
  - `Message`: Email text content

---

## 🔧 Workflow

### 1. Data Preprocessing
- Replaced null values with empty strings
- Converted labels: `spam → 0`, `ham → 1`

### 2. Feature Extraction
- Applied **TF-IDF Vectorizer** to convert text to numerical features

### 3. Model Building
- Trained using **Logistic Regression**
- Used `train_test_split` for splitting data

### 4. Model Evaluation
- Accuracy metric used to evaluate performance

---

## 📊 Model Performance

| Dataset        | Accuracy |
|----------------|----------|
| Training Data  | 96.77%   |
| Test Data      | 96.68%   |

✅ The model shows high and consistent accuracy, indicating strong generalization ability.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

