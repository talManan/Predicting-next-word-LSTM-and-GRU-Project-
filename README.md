# Predicting-next-word-LSTM-and-GRU-Project-

PROJECT OVERVIEW

This project focuses on building an end-to-end Natural Language Processing (NLP) system that predicts the next word in a given text sequence using Recurrent Neural Networks (RNNs).
The models used are LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit), which are well-suited for sequential and language-based tasks.

The project demonstrates the complete workflow:
problem understanding, data preprocessing, model training, prediction, and web app deployment.

PROBLEM STATEMENT

Given a sequence of words, the goal is to predict the most likely next word based on learned patterns from text data.

Example:
Input : "machine learning is"
Output : "powerful"

MODELS USED

LSTM (Long Short-Term Memory)

Handles long-term dependencies

Solves vanishing gradient problem

Suitable for text and sequence data

GRU (Gated Recurrent Unit)

Lightweight alternative to LSTM

Faster training

Comparable performance for sequence tasks

PROJECT STRUCTURE

next-word-prediction/
│
├── data/
│ └── corpus.txt
│
├── notebooks/
│ ├── data_preprocessing.ipynb
│ ├── lstm_model_training.ipynb
│ └── gru_model_training.ipynb
│
├── models/
│ ├── lstm_model.h5
│ └── gru_model.h5
│
├── app.py
├── requirements.txt
└── README.txt

DATA COLLECTION AND PREPROCESSING

Text data is collected from a corpus file

All text is converted to lowercase

Tokenization is performed using a tokenizer

Input sequences are generated using n-grams

Padding is applied to ensure equal sequence length

Output labels are one-hot encoded

MODEL TRAINING

LSTM Model:

Embedding Layer

LSTM Layer

Dense Output Layer with Softmax

Loss Function: Categorical Crossentropy

Optimizer: Adam

GRU Model:

Embedding Layer

GRU Layer

Dense Output Layer with Softmax

Loss Function: Categorical Crossentropy

Optimizer: Adam

PREDICTION WORKFLOW

User provides an input text sequence

Text is tokenized and padded

Model predicts probability distribution of next words

Word with highest probability is selected

Predicted word is appended to input sequence

WEB APPLICATION

Built using Streamlit

User enters a text sentence

Model predicts the next word in real-time

Supports both LSTM and GRU models

HOW TO RUN THE PROJECT

Clone the repository

Install dependencies using:
pip install -r requirements.txt

Run the Streamlit app:
streamlit run app.py

Enter a sentence and get next-word predictions

LIBRARIES USED

Python

NumPy

Pandas

TensorFlow / Keras

Streamlit

Scikit-learn

APPLICATIONS

Text auto-completion

Chatbots

Language modeling

Search engines

AI writing assistants

FUTURE IMPROVEMENTS

Use larger datasets

Add Beam Search for better predictions

Train Transformer-based models

Improve UI and model selection

Add multi-word prediction
