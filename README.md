# 📱 SMS Spam Detection Analysis — NLP

<p align="left">
   <img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/NLP-Text%20Processing-orange" alt="NLP">
  <img src="https://img.shields.io/badge/Accuracy-98.27%25-brightgreen.svg" alt="Accuracy">
  <img src="https://img.shields.io/badge/License-MIT-lightgrey.svg" alt="MIT License">
  <img src="https://img.shields.io/badge/Contributions-Welcome-green.svg" alt="Contributions Welcome">
</p>

---

## 📖 Project Overview  
This project applies **Natural Language Processing (NLP)** techniques and **Machine Learning** algorithms to classify SMS messages as **Spam** or **Ham (legitimate)**.  

It’s a practical demonstration of text preprocessing, feature extraction, and model evaluation — achieving a **best accuracy of 98.27%**.

---

## 📊 Dataset Information  

**Dataset Name:** SMS Spam Collection  
**Total Messages:** 5,574  
**Language:** English  
**Labels:**  
- 📩 `ham` → Legitimate message  
- 🚫 `spam` → Unwanted promotional / fraudulent message  

📥 **Download Dataset:** [Kaggle – SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)

**Description:**  
The dataset includes various spam types such as product ads, scam offers, chain messages, and adult content promotions.

---

## 🧠 Algorithms Used  
| Algorithm | Type | Accuracy |  
|------------|-------|-----------|  
| Logistic Regression | Linear Model | ✅ Excellent |  
| Naive Bayes | Probabilistic | ✅ Excellent |  
| Support Vector Classifier (SVC) | Kernel-based | ✅ Excellent |  
| Random Forest | Ensemble | 🏆 **Best (98.27%)** |  

---

## 🧩 Libraries & Dependencies  
- `pandas` – Data manipulation  
- `numpy` – Numerical computation  
- `nltk` – Text preprocessing (stopwords, stemming)  
- `re` – Regular expressions for text cleaning  
- `scikit-learn` – Feature extraction, model training, and evaluation  

---

## ⚙️ Installation  

### 1️⃣ Create a virtual environment (optional)
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

````

### 2️⃣ Install dependencies

```bash
pip install pandas numpy nltk scikit-learn
```

### 3️⃣ Run the script

```bash
python sms_spam_detection.py
```

---

## 🧹 Preprocessing Steps

* Lowercasing text
* Removing punctuation & special characters using **Regex (`re`)**
* Removing stopwords (using **NLTK**)
* Applying stemming/lemmatization
* Converting text to numerical vectors using **TF-IDF / CountVectorizer**

---

## 📈 Model Evaluation Metrics

* ✅ **Accuracy:** 98.27%
* 📉 **Precision, Recall, F1-Score** used for balanced evaluation
* 📊 **Confusion Matrix** to visualize classification results

---

## 📜 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE).
Feel free to reuse, modify, and share with proper attribution.

---

