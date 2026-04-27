# 🧠 RNN-Based Text Classification (AG News Dataset)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_NOTEBOOK_LINK)

This project builds and compares multiple RNN-based deep learning models for classifying news articles into categories using the AG News dataset.

## 📌 Problem Statement

Classify news articles into one of four categories:

* World
* Sports
* Business
* Sci/Tech

## 🚀 Models Implemented

* Simple RNN
* LSTM
* GRU
* Bidirectional LSTM

## ⚙️ Techniques Used

* Tokenization & Text Preprocessing
* Sequence Padding
* Embedding Layer
* Gradient Clipping
* Model Comparison

## 📊 Results

| Model      | Train Acc | Val Acc | Test Acc |
| ---------- | --------- | ------- | -------- |
| Simple RNN | 28.66%    | 30.49%  | 29.72%   |
| LSTM       | 93.88%    | 90.32%  | 91.17%   |
| GRU        | 96.11%    | 89.67%  | 91.01%   |
| Bi-LSTM    | 97.20%    | 89.40%  | 90.71%   |

## 🔍 Key Insights

* Simple RNN fails to capture long-term dependencies
* LSTM provides the best performance and stability
* GRU achieves similar performance with fewer parameters
* Bi-LSTM increases complexity but does not significantly improve results

## 🧪 Dataset

AG News dataset (via Hugging Face `datasets` library)

## 📈 Conclusion

LSTM is the most effective model for this task, offering the best balance between performance and generalization.

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy, Pandas
* Matplotlib

## 📎 Notebook

Check the full implementation in the Jupyter Notebook.
