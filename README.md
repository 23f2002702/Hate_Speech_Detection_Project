# 🛑 Hate Speech Detection Project

This project aims to detect hate speech and offensive language in tweets using a supervised machine learning approach. The notebook walks through a complete NLP pipeline — from data preprocessing to model evaluation and interpretation.

---

## 📚 Overview

The notebook performs the following steps:

1. 📥 **Import Libraries**  
2. 📊 **Load and Explore Dataset**
3. 🧹 **Text Preprocessing**  
4. 🔠 **Text Vectorization using CountVectorizer**
5. 🤖 **Model Training using Decision Tree**
6. 📈 **Evaluation Metrics and Confusion Matrix**
7. 📊 **Statistical Analysis & Visualization**
8. 🧪 **Testing Model on Custom Input**
9. 🚩 **Username Flagging for Hate/Offensive Content**

---

## 🧠 Model Used

- **Decision Tree Classifier** from `scikit-learn`

---

## 🗂️ Dataset

- The project uses a dataset named `labeled_data.csv` which contains tweets labeled as:
  - `0` – Hate Speech
  - `1` – Offensive Language
  - `2` – Neither (Clean)

---

## 📦 Requirements

Install these Python libraries before running the notebook:

```bash
  pip install pandas numpy matplotlib seaborn scikit-learn nltk 
```

---

## 🚀 How to Run
1. Clone this repo or download the .ipynb file.

2. Place labeled_data.csv in the same directory.

3. Open the notebook in Jupyter or Google Colab.

4. Run all cells sequentially.

---

## 📊 Results & Extras
1. Displays Confusion Matrix, Accuracy, and Classification Report

2. Shows distribution via bar and pie charts

3. Performs real-time prediction on sample texts

4. Flags users with most hate/offensive content

---

## 📝 Example Prediction
``` python
Sample Input: "@@ People against God should be killed."
Predicted Label: Hate Speech
```

---


## 📄 License
This project is released under the MIT License.

---

## ✍️ Author
Shilajit Mukherjee
Data Science Enthusiast | IIT Madras

---
