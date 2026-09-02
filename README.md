# rnn-lstm-deep-learning
Hands-on implementation and practice of Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) networks using TensorFlow/Keras.
This repository contains two NLP projects covering sentiment analysis and next-word prediction, demonstrating how recurrent neural networks can be used to process and learn from sequential text data.
📌 Projects
1. RNN – IMDB Sentiment Analysis
A sentiment classification model built using the IMDB Movie Reviews Dataset.
Objective:
Classify a movie review as either Positive or Negative.
Concepts Covered
Text preprocessing
Tokenization
Word Embeddings
Sequence processing
Recurrent Neural Networks (RNN)
Binary Classification
Model Training & Evaluation
Model Prediction
Technologies
Python
TensorFlow
Keras
NumPy
Pandas
Scikit-learn
Matplotlib
Jupyter Notebook
2. LSTM – Next Word Prediction
A next-word prediction model trained on Hamlet text data using an LSTM network.
Objective:
Given a sequence of words, predict the most likely next word.
Concepts Covered
Text preprocessing
Tokenization
Sequence generation
N-gram sequences
Padding
LSTM Networks
Word Embeddings
Next-word prediction
Model Training
Model Inference
Technologies
Python
TensorFlow
Keras
NumPy
Pandas
Streamlit
Jupyter Notebook
📂 Repository Structure
rnn-lstm-deep-learning/
│
├── RNN_IMDB/
│   ├── embedding.ipynb
│   ├── simplernn.ipynb
│   ├── prediction.ipynb
│   ├── main.py
│   └── simple_rnn_imdb.h5
│
├── LSTM_PREDICTION/
│   ├── experiments.ipynb
│   ├── app.py
│   ├── hamlet.txt
│   ├── predict_next_word_model.h5
│   └── tokenizer.pickle
│
├── requirements.txt
├── .gitignore
└── README.md
