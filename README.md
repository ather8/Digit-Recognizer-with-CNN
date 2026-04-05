## Digit Recognizer with CNN
A Deep Learning project that identifies handwritten digits (0-9) using a Convolutional Neural Network (CNN). This model is trained on the classic MNIST dataset and achieves high accuracy through automated feature extraction.
------------------------------
## 🚀 Project Overview
Handwritten digit recognition is a fundamental "Hello World" project in Computer Vision. Unlike standard Neural Networks, this CNN architecture uses spatial hierarchies to recognize patterns like edges and curves, making it highly effective for image classification.
## Key Features:

* Dataset: MNIST (70,000 grayscale images of $28 \times 28$ pixels).
* Framework: TensorFlow/Keras (or PyTorch).
* Accuracy: ~99% on the test set.
* Visualization: Includes scripts to plot loss/accuracy curves and display sample predictions.

------------------------------
## 🛠️ Tech Stack

* Language: Python 3.x
* Deep Learning: TensorFlow, Keras
* Data Science: NumPy, Pandas, Matplotlib
* Environment: Jupyter Notebook / Google Colab

------------------------------
## 🏗️ Model Architecture
The CNN consists of the following layers:

   1. Conv2D: Filters to detect spatial features.
   2. MaxPooling2D: Downsampling to reduce computational load.
   3. Dropout: To prevent overfitting.
   4. Flatten: Converting 2D maps into a 1D vector.
   5. Dense: Fully connected layers for classification.
   6. Softmax: Output layer providing probabilities for digits 0-9.

------------------------------
## 📋 How to Use## 1. Prerequisites
Install the required libraries:

pip install tensorflow numpy matplotlib pandas

## 2. Run the Notebook

   1. Clone this repository.
   2. Open digit_recognizer.ipynb in Jupyter or Colab.
   3. Run all cells to:
   * Load and normalize the data.
      * Build and train the CNN model.
      * Evaluate performance on test data.
