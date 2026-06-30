
# 🧠 Deep Learning Mini Projects – RNN & LSTM

This repository contains two beginner-friendly Deep Learning projects built using **TensorFlow** and **Keras**.

Projects Included:

1. 🔤 Word Prediction using RNN
2. 📈 Time Series Prediction using LSTM

---

# 🔤 Project 1 – RNN Word Prediction

## Overview

This project uses a **Simple Recurrent Neural Network (RNN)** to predict the next word from text sequences.

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

## Dataset

```text
I love Python
I love Codg
I love You
```

---

## Model Architecture

```text
Embedding
↓
SimpleRNN
↓
Dense (Softmax)
```

### Concepts Covered

- Tokenization
- Embedding Layer
- Text Sequence Encoding
- RNN
- Word Prediction

---

# 📈 Project 2 – LSTM Stock/Sequence Prediction

## Overview

This project uses **Long Short-Term Memory (LSTM)** to predict the next value from previous numerical values.

Example dataset:

```text
100
102
105
107
110
115
120
```

Training Window:

```text
[100 102 105] → 107
[102 105 107] → 110
[105 107 110] → 115
[107 110 115] → 120
```

Prediction Input:

```text
[115 120 125]
```

Predicted Output:

```text
≈ Next Value
```

---

## Model Architecture

```text
LSTM (50 Units)
↓
Dense (1)
```

### Concepts Covered

- Time Series Forecasting
- Sequence Learning
- Data Reshaping
- LSTM Networks

---

# 🛠 Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Google Colab
- Jupyter Notebook

---

# 📦 Installation

Install dependencies:

```bash
pip install tensorflow numpy
```

---

# ▶️ Run

Run notebook:

```bash
jupyter notebook
```

OR

```bash
python project.py
```

---

# 📂 Repository Structure

```text
Deep-Learning-Projects/
│
├── RNN.ipynb
├── LSTM.ipynb
├── README.md
└── screenshots/
```

---

---

# 🎯 Learning Outcomes

After completing this project you will understand:

✅ RNN Architecture  
✅ LSTM Architecture  
✅ Sequence Prediction  
✅ Deep Learning Basics  
✅ TensorFlow Workflow  

---

# 👨‍💻 Author

Harsh Vardhan


---

⭐ Star this repository if you found it useful.
