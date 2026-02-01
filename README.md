# Predicting-next-word-LSTM-and-GRU-Project-


# Next Word Prediction using LSTM & GRU

An end-to-end Deep Learning project that predicts the **next word in a sentence**
using **LSTM and GRU neural networks**, with a real-time **Streamlit web app**.

---

##  Project Overview

This project demonstrates how Recurrent Neural Networks can be used for
Natural Language Processing tasks like next-word prediction.

The complete pipeline includes:
- Data preprocessing
- Model training (LSTM & GRU)
- Prediction logic
- Web app deployment using Streamlit

---

##  Problem Statement

Given a sequence of words, predict the most likely next word.

**Example:**
Input : deep learning is
Output : powerful


---

##  Models Used

- **LSTM (Long Short-Term Memory)**
- **GRU (Gated Recurrent Unit)**

Both models handle sequential data and long-term dependencies effectively.

---

##  Web Application

- Built using **Streamlit**
- User enters a text sentence
- Model predicts the next word in real-time
- Supports both **LSTM** and **GRU** models

---

##  How to Run the Project

1. Clone the repository
git clone <repository-url>
cd next-word-prediction

2. Install dependencies
pip install -r requirements.txt

3. Run the Streamlit app
streamlit run app.py


4. Enter a sentence and get next-word predictions

---

##  Libraries Used

- Python
- NumPy
- Pandas
- TensorFlow / Keras
- Streamlit
- Scikit-learn

---

##  Future Improvements

- Train on larger datasets
- Add beam search for better predictions
- Implement Transformer-based models
- Improve UI and model selection

---




