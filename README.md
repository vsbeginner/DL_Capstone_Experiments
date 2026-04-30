# Capstone Experiments – Deep Learning

Deep Learning experiments implemented using **TensorFlow** and **Keras**, demonstrating how different neural network architectures solve distinct types of machine learning problems.

---

## Overview

This repository contains three practical deep learning experiments:

-  **Feedforward Neural Network (FNN)** → Tabular Classification  
- **Convolutional Neural Network (CNN)** → Image Classification  
- **Long Short-Term Memory (LSTM)** → Time-Series Prediction  

---

## Repository Structure
Capstone_Experiments_DeepLearning/
│
├── Experiment_1.ipynb # FNN – Breast Cancer Classification
├── Experiment_2.ipynb # CNN – Fashion MNIST Classification
├── Experiment_3.ipynb # LSTM – Time Series Prediction
└── README.md


---

## Experiment 1: Feedforward Neural Network (FNN)

### Objective
Classify tumors as **malignant** or **benign** using a dense neural network.

### Dataset
- Breast Cancer Dataset (from Scikit-learn)
- Samples: 569  
- Features: 30  
- Type: Binary Classification  

### Workflow
- Load dataset  
- Normalize features  
- Train-test split  
- Build dense neural network  
- Apply dropout regularization  
- Train and evaluate model  

### Model Architecture
- Input Layer  
- Dense Layer (ReLU)  
- Dropout Layer  
- Dense Output Layer (Sigmoid)  

### Outputs
- Accuracy vs Epoch graph  
- Loss vs Epoch graph  
- Classification performance evaluation  

---

## Experiment 2: Convolutional Neural Network (CNN)

### Objective
Classify grayscale fashion images into **10 categories**.

### Dataset
- Fashion-MNIST  
- Training Images: 60,000  
- Testing Images: 10,000  
- Classes: 10  

### Example Classes
- T-shirts  
- Shirts  
- Sneakers  
- Bags  
- Dresses  

### Workflow
- Normalize pixel values  
- Reshape dataset  
- Build CNN architecture  
- Apply MaxPooling  
- Add Dropout  
- Train and evaluate model  

### Model Architecture
- Conv2D  
- MaxPooling2D  
- Conv2D  
- MaxPooling2D  
- Flatten  
- Dense  
- Dropout  
- Softmax Output Layer  

### Outputs
- Training accuracy graph  
- Validation accuracy graph  
- Loss vs Epoch graph  

---

## Experiment 3: LSTM for Time-Series Prediction

### Objective
Predict sequential values using LSTM networks.

### Dataset
- Synthetic sine wave dataset  
- Demonstrates sequence learning  

### Workflow
- Generate sine wave data  
- Create input sequences  
- Train-test split  
- Build LSTM model  
- Apply EarlyStopping  
- Predict future values  
- Compare predictions with actual values  

### Model Architecture
- LSTM Layer  
- Dropout Layer  
- Dense Output Layer  

### Outputs
- Predicted vs Actual signal plot  
- Training loss visualization  

---

## Technologies Used

| Tool | Purpose |
|------|--------|
| Python | Programming Language |
| TensorFlow / Keras | Deep Learning Framework |
| NumPy | Numerical Computation |
| Matplotlib | Visualization |
| Scikit-learn | Dataset & Preprocessing |

---

## How to Run
Launch Jupyter Notebook:
jupyter notebook
Run experiments in order:
Experiment_1.ipynb
Experiment_2.ipynb
Experiment_3.ipynb
Execute all cells sequentially.

---

Author
Vinayak Sharma 

Github:https://github.com/vsbeginner

Linkedin:https://www.linkedin.com/in/vinayak-sharma-24a8aa384/
