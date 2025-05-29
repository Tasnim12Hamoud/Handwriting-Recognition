# Handwriting-Recognition
A deep learning project with a graphical interface that allows users to draw handwritten English letters (A-Z) and recognizes them using a trained Convolutional Neural Network (CNN) model.

# 🖌️ Handwritten Character Recognition with Drawing GUI

This project demonstrates a deep learning model for recognizing handwritten English characters (A–Z) using a Convolutional Neural Network (CNN). It features a simple graphical user interface (GUI) built with `Tkinter` that allows users to draw characters using the mouse, then the trained model predicts the character.

## 📌 Features
- Handwritten character recognition (A–Z)
- CNN-based model built with TensorFlow/Keras
- GUI for drawing and prediction using `Tkinter`
- Trained on the EMNIST Letters dataset

## 🧠 Model Architecture
- 2 Convolutional layers + MaxPooling
- Flatten + Dense layer with Dropout
- Output: 26 softmax neurons for 26 English letters

## 📂 Dataset
- EMNIST Letters dataset (available from `tensorflow_datasets` or `.csv`)
- Classes: 26 English capital letters (A–Z)
