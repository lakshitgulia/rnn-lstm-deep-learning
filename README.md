# RNN & LSTM Deep Learning Projects

Hands-on implementation of Recurrent Neural Networks (RNN) and LSTM networks using TensorFlow/Keras, covering sentiment analysis and next-word prediction on sequential text data.

## 📌 Projects

### 1. RNN – IMDB Sentiment Analysis
Classifies movie reviews as **Positive** or **Negative** using the IMDB dataset.

**Concepts:** Text preprocessing, tokenization, word embeddings, sequence processing, RNNs, binary classification, model training & evaluation.

**Tech stack:** Python, TensorFlow, Keras, NumPy, Pandas, Scikit-learn, Matplotlib, Jupyter Notebook

### 2. LSTM – Next Word Prediction
Predicts the next word in a sequence, trained on Hamlet text data.

**Concepts:** Text preprocessing, tokenization, n-gram sequences, padding, LSTM networks, word embeddings, model inference.

**Tech stack:** Python, TensorFlow, Keras, NumPy, Pandas, Streamlit, Jupyter Notebook

## 📂 Repository Structure
rnn-lstm-deep-learning/
│
├── RNN_IMDB/
│ ├── embedding.ipynb
│ ├── simplernn.ipynb
│ ├── prediction.ipynb
│ ├── main.py
│ └── simple_rnn_imdb.h5
│
├── LSTM_PREDICTION/
│ ├── experiments.ipynb
│ ├── app.py
│ ├── hamlet.txt
│ ├── predict_next_word_model.h5
│ └── tokenizer.pickle
│
├── requirements.txt
├── .gitignore
└── README.md