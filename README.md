# SIMPLE_RNN

# 🎬 IMDB Movie Review Sentiment Analysis

This is a web application built using **Streamlit** and **TensorFlow** to classify IMDB movie reviews as **positive** or **negative** based on user input. The model is a simple RNN trained on the IMDB dataset from Keras.

---

## 🚀 Features

- Accepts raw text reviews from users
- Preprocesses text to match the model's training format
- Uses a pre-trained RNN model (`simple_rnn_imdb.h5`)
- Classifies sentiment as **Positive** or **Negative**
- Displays a confidence score (prediction probability)

---

## 🧠 Model

- Trained on the [IMDB dataset](https://keras.io/api/datasets/imdb/)
- Uses word indexing and padding to prepare sequences
- The RNN model (`simple_rnn_imdb.h5`) must be available in the same directory

---

## 🛠️ Installation

1. Clone this repository or download the source code.

2. Install dependencies:

```bash
pip install -r requirements.txt
