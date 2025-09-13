# 🧠 MNIST Digit Classifier using TensorFlow & Keras

This repository contains an implementation of a **handwritten digit classifier** built using **TensorFlow** and **Keras**.  
The model is trained on the **MNIST dataset**, which is a benchmark dataset in deep learning and computer vision.

---

## 📊 Dataset

- **MNIST (Modified National Institute of Standards and Technology) dataset**
  - 60,000 training images
  - 10,000 test images
  - Each image is **28×28 grayscale** (values range from 0 to 255)
- Labels: Digits from **0 to 9**

Example of MNIST digits:

![MNIST sample](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

---

## ⚙️ Technologies Used

- **Programming Language:** Python 🐍  
- **Frameworks/Libraries:**
  - TensorFlow & Keras (Deep Learning)
  - NumPy (Data handling)
  - Matplotlib (Visualization)
  - Jupyter Notebook (Development environment)

---

## 🚀 Model Architecture

- Input layer: Flatten 28×28 image → 784 neurons  
- Hidden layers: One Dense layer with **ReLU activation** and 512 neurons
- Output layer: 10 neurons with **Softmax activation**  

Training configuration:
- Loss function: Sparse categorical crossentropy  
- Optimizer: SGD  
- Metric: Accuracy  

---

## 📈 Training & Results

- Epochs trained: 100  
- Batch size: 128  
- Accuracy achieved:
  - Training accuracy: ~92%  
  - Test accuracy: ~92%  

> ⚡ Note: Accuracy may vary slightly depending on random initialization and training epochs.

---