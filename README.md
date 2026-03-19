# 🧠 MBTI Personality Classifier

### NLP with Deep Learning (BiLSTM + GloVe)

---

## 📌 Overview

This project is a **Deep Learning-based NLP application** that predicts a user’s **MBTI (Myers-Briggs Type Indicator) personality type** from text.

The model analyzes written text and classifies personality across **4 psychological axes**:

* Introversion (I) vs Extraversion (E)
* Intuition (N) vs Sensing (S)
* Thinking (T) vs Feeling (F)
* Judging (J) vs Perceiving (P)

---

## 🚀 Features

* 🔮 Predict MBTI personality from user text
* 📊 Interactive analytics dashboard (charts & visualizations)
* 📂 Batch prediction using CSV upload
* 🔍 Explore all 16 personality types
* 🌐 Web app built using Streamlit

---

## 🧠 Model Details

* Model: **Bidirectional LSTM (BiLSTM)**
* Embeddings: **GloVe (50-dimensional)**
* Task: **Multi-output classification (4 axes)**
* Dataset: MBTI dataset (~8,675 samples)
* Input: User posts/text
* Output: MBTI type (e.g., INTJ, ENFP)

---

## 🏗️ Project Structure

```
mbti-streamlit/
│
├── app.py                  # Main Streamlit app
├── model/
│   ├── mbti_bilstm_model.keras
│   └── tokenizer.pkl
│
├── pages/
│   ├── home.py
│   ├── predictor.py
│   ├── analytics.py
│   ├── batch.py
│   └── explorer.py
│
├── utils/
│   ├── mbti_data.py
│   └── predictor.py
│
└── assets/
    └── confusion_matrices.png
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/mbti-classifier.git
cd mbti-classifier
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the app

```bash
streamlit run app.py
```

---

## 🌐 Deployment (Colab + ngrok)

This project can also be run in **Google Colab** using:

* Streamlit server
* ngrok for public URL access

---

## 📊 Example Output

* Predicted Type: **INTJ — The Architect**
* Confidence Scores for each axis
* Visualizations (Radar chart, Bar chart, Confusion Matrix)

---

## 📈 Evaluation Metrics

* Accuracy (per axis)
* Macro F1-score
* Confusion Matrix

---

## 🧪 Sample Input

```
"I love spending time alone reading and thinking about abstract ideas."
```

### Output:

```
INTJ — The Architect
```

---

## 🛠️ Technologies Used

* Python 🐍
* TensorFlow / Keras
* Scikit-learn
* Pandas & NumPy
* Streamlit
* Plotly & Matplotlib

---

## 🎯 Future Improvements

* Improve accuracy with larger datasets
* Use Transformer models (BERT, RoBERTa)
* Deploy on cloud platforms (AWS / GCP)
* Add user authentication

---

## 👩‍💻 Author

**Aiswarya Mohan**
M.Tech – Computer Science

---

## ⭐ Acknowledgements

* MBTI dataset from Kaggle
* GloVe embeddings (Stanford NLP)

---

## 📬 Contact

Feel free to reach out for collaboration or questions!

---
