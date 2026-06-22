# 🎬 Simple RNN Movie Review Sentiment Analysis

A Deep Learning project that classifies IMDB movie reviews as **Positive** or **Negative** using a **Simple Recurrent Neural Network (SimpleRNN)** built with TensorFlow/Keras and deployed with Streamlit.

---

## 📌 Project Overview

Sentiment Analysis is a Natural Language Processing (NLP) task that determines the emotional tone behind a piece of text.

This project uses the IMDB Movie Review Dataset to train a SimpleRNN model capable of understanding the sentiment of user-provided movie reviews.

---

## 🚀 Features

* Predicts movie review sentiment (Positive / Negative)
* Trained on the IMDB Dataset
* Text preprocessing and tokenization
* Deep Learning model using SimpleRNN
* Interactive Streamlit web application
* Real-time sentiment prediction

---

## 🧠 Model Architecture

```python
Embedding(input_dim=10000, output_dim=128)
SimpleRNN(128, activation='relu')
Dense(1, activation='sigmoid')
```

### Training Configuration

* Dataset: IMDB Movie Reviews
* Vocabulary Size: 10,000 words
* Sequence Length: 500
* Embedding Dimension: 128
* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Evaluation Metric: Accuracy

### Performance

* Test Accuracy: ~82%

---

## 📂 Project Structure

```text
simple-rnn-movie-review-sentiment-analysis/
│
├── app.py
├── simplernn.ipynb
├── prediction.ipynb
├── embedding.ipynb
├── simple_rnn_imdb.keras
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/amnsingh05/simple-rnn-movie-review-sentiment-analysis.git
cd simple-rnn-movie-review-sentiment-analysis
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Open your browser and visit:

```text
http://localhost:8501
```

---

## 📝 Example Reviews

### Positive

> This movie was fantastic! The acting was great and the plot was thrilling.

### Negative

> This movie was boring and a complete waste of time.

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Streamlit
* Jupyter Notebook
* NLP

---

## 📚 Concepts Used

* Natural Language Processing (NLP)
* Word Embeddings
* Sequence Padding
* Recurrent Neural Networks (RNN)
* Sentiment Analysis
* Deep Learning

---

## 👨‍💻 Author

**Aman Singh**

GitHub: https://github.com/amnsingh05

LinkedIn: https://www.linkedin.com/in/amnsingh0

---

⭐ If you found this project useful, consider giving it a star on GitHub!
