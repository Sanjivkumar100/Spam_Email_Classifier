# 📧 Spam Email Detection

## 🔍 Project Description

This project detects whether an email is **Spam** or **Not Spam** using an **LSTM-based Deep Learning model**.
A **Gradio interface** is provided so users can type or paste email text and instantly get predictions.

---

## ⚙️ Requirements

Install the required libraries:

```bash
pip install tensorflow nltk gradio scikit-learn pandas numpy
```

---

## 🧠 Model

* **Embedding Layer** for word representation
* **LSTM Layer** for sequence learning
* **Dense Layers** for classification
* **Sigmoid Output** for binary prediction

---

## ▶️ Usage

### 1. Train the model

```bash
python train.py
```

### 2. Run the Gradio App

```bash
python app.py
```

This will launch a **local web app** where you can enter an email text and see whether it’s spam or not.

---

## 🌐 Example

**Input:**

```
Congratulations! You won a lottery of $10,000. Claim now!
```

**Output:**

```
Prediction: Spam  
Confidence: 0.98
```

**Input:**

```
Hi John, let’s meet tomorrow at the office to finalize the report.
```

**Output:**

```
Prediction: Not Spam  
Confidence: 0.91
```

---

## 🚀 Future Scope

* Add more training data for better accuracy
* Try advanced models (BiLSTM, GRU, Transformers)
* Deploy on Hugging Face / Streamlit Cloud

---
