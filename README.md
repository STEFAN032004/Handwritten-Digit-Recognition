# Hand-written-digit-recognition

This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits from images. The MNIST dataset is used for training and testing the model, which achieves high accuracy. Uploaded digit images are preprocessed using OpenCV (grayscale, resize, blur, and threshold). The model predicts the digit, and the result is displayed with matplotlib. It runs in a loop to continuously accept and classify user-uploaded digit images.
# Handwritten Digit Recognition

This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits (0–9) from images.

## 🔧 Technologies Used
- Python
- OpenCV
- NumPy
- Keras / TensorFlow

## 🧠 Features
- Image preprocessing
- CNN model training
- Real-time digit prediction

## ▶️ How to Run
1. Clone the repo  
2. Install required libraries  
```bash
pip install -r requirements.txt
python digit_recognition.py
