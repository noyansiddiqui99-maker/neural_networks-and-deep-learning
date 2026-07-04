# 🧠 Neural Network Classification with PyTorch

> Learning PyTorch by building binary and multi-class neural network classifiers from scratch.

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?logo=pytorch)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Overview

This repository documents my journey of understanding **Neural Network Classification** using **PyTorch**. Rather than relying on high-level libraries, I implemented classification models step by step to understand how neural networks learn decision boundaries.

The project explores both **Binary Classification** and **Multi-Class Classification**, covering everything from dataset creation to model evaluation.

---

## 📂 Repository Structure

```
📦 Neural-Network-Classification
│
├── classification_nn.ipynb
│   └── Binary Classification using Neural Networks
│
├── binary_and_multi_class_classification_nn.ipynb
│   └── Binary + Multi-Class Classification
│
└── README.md
```

---

# 🚀 Topics Covered

✅ Data Generation using Scikit-Learn

✅ Exploratory Data Analysis (EDA)

✅ Data Visualization

✅ Tensor Conversion

✅ Train/Test Splitting

✅ Building Neural Networks with PyTorch

✅ Loss Functions

✅ Optimizers

✅ Training Loops

✅ Prediction & Evaluation

✅ Binary Classification

✅ Multi-Class Classification

✅ Decision Boundaries

---

# 📖 Notebook 1
## Binary Classification (`classification_nn.ipynb`)

This notebook focuses on solving a **non-linear binary classification** problem using the classic **make_circles()** dataset.

### What I implemented

- Creating synthetic datasets using `make_circles`
- Visualizing circular datasets
- Preparing tensors for PyTorch
- Building custom `nn.Module` models
- Binary classification with
  - `BCEWithLogitsLoss`
  - Sigmoid activation
- Model training
- Loss monitoring
- Accuracy calculation
- Improving performance using hidden layers
- Experimenting with non-linear activation functions

---

# 📖 Notebook 2
## Binary & Multi-Class Classification (`binary_and_multi_class_classification_nn.ipynb`)

This notebook expands on binary classification by introducing **multi-class learning**.

### Implementations include

- Binary Classification Review
- Multi-Class Dataset Generation using `make_blobs`
- Multi-Class Neural Networks
- Softmax Predictions
- CrossEntropyLoss
- Class Prediction using `torch.argmax`
- Accuracy Evaluation
- Understanding Linear vs Non-linear Problems
- Effect of Activation Functions like ReLU

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Deep Learning | PyTorch |
| Machine Learning | Scikit-Learn |
| Data Analysis | Pandas |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |
| Environment | Jupyter Notebook |

---

# 🧠 Machine Learning Workflow

```text
Dataset
    │
    ▼
Data Exploration
    │
    ▼
Visualization
    │
    ▼
Train-Test Split
    │
    ▼
Tensor Conversion
    │
    ▼
Model Architecture
    │
    ▼
Loss Function
    │
    ▼
Optimizer
    │
    ▼
Training Loop
    │
    ▼
Prediction
    │
    ▼
Evaluation
```

---

# 📊 Learning Outcomes

Through these notebooks I learned how to:

- Build neural networks from scratch using PyTorch
- Understand binary and multi-class classification
- Design custom neural network architectures
- Choose appropriate loss functions
- Train models using Gradient Descent
- Improve classification performance using hidden layers
- Understand why activation functions are necessary
- Evaluate predictions using accuracy metrics
- Interpret model outputs using logits, probabilities and predicted classes

---

# 🎯 Future Improvements

- [ ] Add Decision Boundary Visualization
- [ ] TensorBoard Integration
- [ ] Hyperparameter Tuning
- [ ] Model Checkpoint Saving
- [ ] Early Stopping
- [ ] Precision, Recall & F1 Score
- [ ] Confusion Matrix
- [ ] GPU Benchmarking

---

# 📚 Key Concepts Practiced

- Binary Classification
- Multi-Class Classification
- Feed Forward Neural Networks
- BCEWithLogitsLoss
- CrossEntropyLoss
- SGD Optimizer
- Hidden Layers
- ReLU Activation
- Softmax
- Sigmoid
- Logits
- PyTorch Tensors
- Model Training
- Model Evaluation

---

## 👨‍💻 Author

**Noyan Siddiqui**

Data Science Undergraduate passionate about Artificial Intelligence, Machine Learning, Deep Learning, and Full-Stack Development.

> *Learning by building, experimenting, and understanding how intelligent systems work under the hood.*

---
⭐ If you found this project interesting, consider giving it a star!
