# Gujarati Character Recognition with PyQt5 GUI (Project #09)

The ninth project in my **AI/ML Learning Path**. This project focuses on **Optical Character Recognition (OCR)** for the Gujarati script, combined with a desktop application interface built using **PyQt5**.

## 📌 Overview
Gujarati is a rich, complex script with unique structural features. This project implements a Convolutional Neural Network (CNN) to classify handwritten Gujarati characters and provides a user-friendly GUI for real-time interaction and visualization.

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning Framework:** TensorFlow / Keras
* **GUI Framework:** PyQt5
* **Image Processing:** OpenCV, PIL
* **Libraries:** NumPy, Matplotlib

## 🏗️ Project Structure
1. **The Model:** A CNN architecture optimized for grayscale character images (typically 32x32 or 64x64 pixels).
2. **The Dataset:** Trained on a dataset of handwritten Gujarati characters (Vowels/Consonants).
3. **The Interface:** A PyQt5 application featuring:
    - An "Upload Image" button.
    - A "Predict" button.
    - A display area to show the input image and the predicted character in both text and probability format.

## ⚙️ How It Works
1. **Preprocessing:** The input image is converted to grayscale, inverted (if necessary), and resized to match the model's training input.
2. **Inference:** The CNN extracts spatial features through multiple convolution and pooling layers.
3. **GUI Integration:** The PyQt5 backend handles the signal/slot mechanism to pass the image to the model and return the result to the main window.

## 🚀 Quick Start
1. **Install Dependencies:**
   ```bash
   pip install tensorflow pyqt5 opencv-python pillow
2. **Run the application**
   ```bash
   python main.py
3. **Usage**
   Upload a handwritten Gujarati character image and click "Predict" to see the model in action.

*Progress: Successfully integrated Deep Learning with GUI Development.*
