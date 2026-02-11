# handwritten-digit-recognition


## 📌 Project Overview
This project implements a **Convolutional Neural Network (CNN)** to classify handwritten digits (0-9) from the famous **MNIST dataset**. The model is built using **Python** and **TensorFlow/Keras**, achieving high accuracy by effectively capturing spatial hierarchies in image data.

This project demonstrates the end-to-end Machine Learning pipeline: data preprocessing, model architecture design, training, and evaluation.

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow, Keras
* **Data Manipulation:** NumPy, Pandas
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## 📂 Dataset
* **Source:** [MNIST Dataset](http://yann.lecun.com/exdb/mnist/) (Loaded directly via Keras API)
* **Training Set:** 60,000 images of handwritten digits.
* **Test Set:** 10,000 images.
* **Image Shape:** 28x28 grayscale pixels.

## 🏗️ Model Architecture
I utilized a Sequential CNN architecture designed to capture local patterns:
1.  **Input Layer:** Reshaped data to (28, 28, 1).
2.  **Convolutional Layers:** Extracted features using filters (kernels).
3.  **Pooling Layers (MaxPooling):** Reduced dimensionality to prevent overfitting and reduce computation.
4.  **Flatten Layer:** Converted 2D feature maps into a 1D vector.
5.  **Dense Layers (Fully Connected):** Performed classification.
6.  **Output Layer:** Softmax activation with 10 neurons (for digits 0-9).

## 📊 Results
* **Training Accuracy:** ~99%
* **Test Accuracy:** ~98%
* **Evaluation:** Generated a Confusion Matrix to visualize misclassifications.

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/Handwritten-Digit-Recognition.git](https://github.com/YourUsername/Handwritten-Digit-Recognition.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install tensorflow pandas numpy matplotlib seaborn
    ```
3.  **Run the notebook:**
    Open `Handwritten_Digit_Recognition.ipynb` in Jupyter Notebook or Google Colab and run all cells.

## 🔮 Future Improvements
* Implement a GUI (using Tkinter or Streamlit) to draw digits on screen for real-time prediction.
* Experiment with Data Augmentation to further improve robustness.

---
*Created by [Anushka Ranjan](https://www.linkedin.com/in/anushka-ranjan-6b5499311)*
