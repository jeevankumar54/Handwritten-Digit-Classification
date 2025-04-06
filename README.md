# Handwritten Digits Classification 🧠✍️

This project demonstrates a basic image classification model trained to recognize handwritten digits (0–9) using the popular MNIST dataset. The model is built using a simple neural network with TensorFlow and Keras.

## 🧾 Features

- Uses MNIST dataset (60,000 training, 10,000 testing images)
- Neural network with dense layers
- Achieves over 97% accuracy on test data
- Clean visualization of loss and accuracy
- Written in an easy-to-follow Jupyter Notebook format

## 🛠️ Tech Stack

- Python 🐍
- TensorFlow / Keras 📚
- Matplotlib 📊
- NumPy 🔢
- Jupyter Notebook 📓

## 📁 Files

- `Handwitten_Digits_Classification.ipynb` – Main notebook with model implementation and evaluation

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/handwritten-digits-classification.git
   cd handwritten-digits-classification

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the notebook:
   ```bash
   jupyter notebook Handwitten_Digits_Classification.ipynb

## ✅ Requirements

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- Jupyter

You can generate a `requirements.txt` file using:
   ```bash
   pip freeze > requirements.txt
   ```

## 📈 Results

- Final test accuracy: ~97%
- Loss and accuracy plots included

## 📸 Confusio Matrix
- Before adding a hidden layer
  ![Confusion Matrix before adding hidden layer]()

- After adding a hidden layer
  ![Confusion Matrix after adding hidden layer](https://github.com/jeevankumar54/Handwritten-Digit-Classification/blob/cdfb56ae55be8261ecefee259356842b09d1b308/Confusion%20Matrix.png)

## 📌 Future Improvements

- Implement CNN for improved accuracy
- Try using dropout/regularization
- Convert the notebook to a Python script and deploy as a simple web app using Streamlit
