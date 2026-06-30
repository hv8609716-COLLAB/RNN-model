# RNN-model



# 🧠 RNN Word Prediction using TensorFlow

A simple Deep Learning project built using **TensorFlow**, **Keras**, and **SimpleRNN** to predict the next word from a small text dataset.

---

## 🚀 Project Overview

This project demonstrates how a **Recurrent Neural Network (RNN)** can learn patterns from text sequences and predict output words.

Example:

Input:
```
I love
```

Output:
```
Python
Codg
You
```

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Google Colab / Jupyter Notebook

---

## 📂 Dataset

Training Sentences:

```text
I love Python
I love Codg
I love You
```

---

## 🧠 Model Architecture

```text
Embedding Layer
↓
SimpleRNN Layer
↓
Dense Layer (Softmax)
```

### Model Parameters

- Embedding Output Dimension → 5
- RNN Units → 10
- Epochs → 200
- Optimizer → Adam
- Loss → Sparse Categorical Crossentropy

---

## ▶️ Installation

Install dependencies:

```bash
pip install tensorflow numpy
```

---

## ▶️ Run Project

```bash
python rnn.py
```

OR

Run directly in:

- Google Colab
- Jupyter Notebook

---

## 📌 Output Example

```text
Predicted Words:
Python
Codg
You
```

---

## 📈 Learning Concepts

This project covers:

- Tokenization
- Text to Sequence Conversion
- Embedding Layer
- Recurrent Neural Networks (RNN)
- Word Prediction
- Model Training

---
NOTE: This is example 
## 👨‍💻 Author

Harsh Vardhan


---
