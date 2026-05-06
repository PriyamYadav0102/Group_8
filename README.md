# 📧 Email Spam Detection System

A machine learning-based system to classify emails as **spam or not spam** using traditional models, rule-based filtering, and transformer-based NLP.

---

## 📌 Overview

This project builds a **hybrid spam detection system** combining:

* Classical machine learning models
* Rule-based keyword filtering
* Transformer-based deep learning (DistilBERT)

The goal is to improve classification accuracy and demonstrate different approaches to text classification.

---

## 👥 Team Members

* Dev Modi
* Roshan Pattharwala
* Priyam yadav
---

## 🧠 Features

* Exploratory Data Analysis (EDA) with visualizations
* Text preprocessing and cleaning
* Machine Learning models:

  * Naive Bayes
  * Logistic Regression
* Cross-validation for model evaluation
* Hybrid rule-based spam filtering
* Transformer-based classification using DistilBERT
* Performance comparison of models
---

## 📂 Project Structure

```
project/
│
├── notebooks/
│   └── email_spam.ipynb     # Main notebook
├── data/                    # Dataset (if included)
├── outputs/                 # Results & visualizations
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/your-username/email-spam-detection.git
cd email-spam-detection
```

Install dependencies:

```
pip install -r requirements.txt
```

Or install manually:

```
pip install pandas numpy matplotlib seaborn scikit-learn transformers datasets wordcloud
```

---

## ▶️ Usage

Run the notebook using Jupyter:

```
jupyter notebook
```

Then open:

```
notebooks/email_spam.ipynb
```

Upload your dataset when prompted.

---

## 📊 Models Used

### 🔹 Traditional Models

* Naive Bayes (TF-IDF)
* Logistic Regression

### 🔹 Hybrid Approach

* Keyword-based spam filtering (e.g., "free", "win", "urgent")

### 🔹 Deep Learning

* DistilBERT transformer model via Hugging Face

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Cross-validation scores

---

## 🧪 Example Output

The system:

* Classifies random emails
* Compares model predictions
* Shows performance metrics

---

## 🚧 Limitations

* Requires dataset upload manually
* Transformer model may be slower
* Rule-based system is simplistic

---

## 🔮 Future Improvements

* Deploy as a web app (Flask/Streamlit)
* Use larger datasets
* Fine-tune transformer model
* Real-time spam detection

---

## 📜 License

This project is for academic purposes.

---

## 🙌 Acknowledgements

* Hugging Face Transformers
* Scikit-learn
* Dataset source (add yours, e.g., Kaggle)

---
