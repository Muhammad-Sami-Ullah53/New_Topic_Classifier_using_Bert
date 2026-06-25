# 📰 BERT News Topic Classifier

### 🚀 Fine-Tuned Transformer for Automated News Categorization

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=28&duration=3000&pause=1000&color=36BCF7&center=true&vCenter=true&width=900&lines=BERT+News+Topic+Classifier;Natural+Language+Processing+Project;Transformer+Based+Text+Classification;Fine-Tuned+on+AG+News+Dataset" />
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge\&logo=python)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow?style=for-the-badge\&logo=huggingface)
![BERT](https://img.shields.io/badge/BERT-NLP-green?style=for-the-badge)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red?style=for-the-badge\&logo=pytorch)
![Gradio](https://img.shields.io/badge/Gradio-WebApp-orange?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-AGNews-purple?style=for-the-badge)

</p>

---

# 🌟 Project Overview

This project leverages the power of **BERT (Bidirectional Encoder Representations from Transformers)** to automatically classify news headlines into four categories:

| Label | Category |
| ----- | -------- |
| 🌍 0  | World    |
| ⚽ 1   | Sports   |
| 💹 2  | Business |
| 🔬 3  | Sci/Tech |

The model is fine-tuned using the **AG News Dataset** and deployed through **Gradio** for real-time predictions.

---

# 🎯 Problem Statement

Thousands of news articles are published every minute.

Manual categorization is:

❌ Slow

❌ Expensive

❌ Error-Prone

This project automates the process using state-of-the-art Transformer architecture.

---

# 🏗️ System Architecture

```mermaid
flowchart LR

A[News Headline] --> B[BERT Tokenizer]

B --> C[Input IDs]
B --> D[Attention Mask]

C --> E[BERT Model]
D --> E

E --> F[Classification Head]

F --> G[World]
F --> H[Sports]
F --> I[Business]
F --> J[Sci/Tech]
```

---

# 🔥 Key Features

✅ Fine-Tuned BERT Model

✅ Transfer Learning

✅ Hugging Face Transformers

✅ AG News Dataset

✅ Real-Time Gradio Deployment

✅ Accuracy & F1 Evaluation

✅ Multi-Class Classification

✅ Production Ready Structure

---

# 🛠️ Tech Stack

```text
Programming Language
│
├── Python
│
Machine Learning
│
├── PyTorch
├── Transformers
├── Datasets
└── Scikit-Learn
│
Deployment
│
└── Gradio
│
Visualization
│
├── Pandas
└── Matplotlib
```

---

# 📂 Project Structure

```bash
BERT-News-Classifier/
│
├── notebook/
│   └── news_classifier.ipynb
│
├── bert_ag_news/
│   ├── config.json
│   ├── tokenizer.json
│   ├── vocab.txt
│   └── pytorch_model.bin
│
├── screenshots/
│   ├── prediction.png
│   ├── confusion_matrix.png
│   └── training_curves.png
│
├── requirements.txt
│
└── README.md
```

---

# 🔄 Machine Learning Workflow

```mermaid
graph TD

A[Load Dataset]
--> B[Preprocessing]

B --> C[Tokenization]

C --> D[BERT Fine Tuning]

D --> E[Model Evaluation]

E --> F[Save Model]

F --> G[Deploy with Gradio]

G --> H[Live Predictions]
```

---

# 📊 Dataset Information

### AG News Dataset

| Property         | Value   |
| ---------------- | ------- |
| Classes          | 4       |
| Total Samples    | 127,600 |
| Training Samples | 120,000 |
| Testing Samples  | 7,600   |
| Language         | English |

---

# 📈 Dataset Distribution

```text
World      ████████████████████████ 30,000
Sports     ████████████████████████ 30,000
Business   ████████████████████████ 30,000
Sci/Tech   ████████████████████████ 30,000
```

Balanced dataset → Better training performance.

---

# 🧠 Why BERT?

Traditional ML Models:

❌ Limited Context

❌ Poor Semantic Understanding

❌ Manual Feature Engineering

BERT:

✅ Context-Aware

✅ Bidirectional Learning

✅ Transfer Learning

✅ State-of-the-Art NLP Performance

---

# 🚀 Training Configuration

```python
Model               : bert-base-uncased
Epochs              : 3
Batch Size          : 16
Max Length          : 128
Optimizer           : AdamW
Evaluation Metric   : Accuracy + F1 Score
Framework           : Hugging Face Trainer
```
