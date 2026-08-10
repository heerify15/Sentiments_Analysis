# 🎬 Sentiments Analysis

## 📌 Overview

A **Natural Language Processing (NLP)** project that uses a **Recurrent Neural Network (RNN)** built with **PyTorch** to classify IMDB movie reviews as **Positive** or **Negative**.

## 📂 Dataset

**IMDB Movie Reviews Dataset**

* Binary sentiment classification
* `0` → Negative
* `1` → Positive

## 🧠 Model Architecture

```text
Movie Review
     ↓
Text Preprocessing
     ↓
Tokenization & Padding
     ↓
Embedding
     ↓
RNN
     ↓
Fully Connected Layer
     ↓
Positive / Negative
```

## 🛠️ Technologies

* PyTorch
* Scikit-learn
* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn

## 📊 Results

| Metric    |      Score |
| --------- | ---------: |
| Accuracy  | **88.99%** |
| Precision | **89.02%** |
| Recall    | **88.99%** |
| F1 Score  | **88.99%** |

## 📁 Folder Structure

```text
Sentiment-Analysis-RNN/
│
├── Notebook/
│   └── RNN_Sentiments_Analysis.ipynb
│
├── models/
│   └── best_RNN_model.pt
│
├── Output/
│   ├── confusion_matrix.png
│   └── loss_curve.png
│
├── README.md
```

## 🎯 Key Learning

* Text prep-rocessing and tokenization
* Sequence padding
* Word embeddings
* RNN-based text classification
* Model training and validation
* Classification metrics and visualization

## 🔮 Future Improvements

* Compare **RNN, LSTM, and GRU**
* Experiment with pretrained embeddings
* Explore Transformer-based sentiment analysis
