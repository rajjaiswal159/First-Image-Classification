# 🧠 Handwritten Digit Classification using CNN

This project demonstrates how to build a Convolutional Neural Network (CNN) using TensorFlow to classify handwritten digits from the MNIST dataset.

<br>

## 📌 Overview

- Dataset: [MNIST Handwritten Digits](http://yann.lecun.com/exdb/mnist/)
- Task: Image Classification (Digits 0–9)
- Framework: TensorFlow / Keras
- Model Type: Convolutional Neural Network (CNN)

<br>

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Matplotlib, Seaborn

<br>

## 🧪 Model Architecture

- **Conv2D** with 32 filters + MaxPooling
- **Conv2D** with 64 filters + MaxPooling
- **Flatten**
- **Dense** layer with 128 neurons + Dropout
- **Output** layer with Softmax (10 classes)

<br>

## 📊 Results

- **Final Validation Accuracy:** ~99%
- **Loss Function:** Sparse Categorical CrossEntropy (log loss)
- **Optimizer:** Adam

> 📉 Training curves and evaluation metrics are included in the notebook.

<br>

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/rajjaiswal159/First-Image-Classification.git
   cd First-Image-Classification
Install dependencies:
```bash
pip install -r requirements.txt
```
Run the notebook:

Open Handwritten-Digit-Classification.ipynb in Jupyter or Google Colab.

<br>
📁 Project Structure
├── Handwritten-Digit-Classification.ipynb ||
├── README.md ||
└── requirements.txt
<br>
📸 Sample Predictions
You can visualize a few test image predictions from the trained model in the notebook.

<br>
🙌 Acknowledgments
- MNIST Dataset

- TensorFlow & Keras Documentation
