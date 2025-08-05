# 🧠 MNIST Digit Classifier with TensorFlow & Keras

A simple yet powerful neural network model built using TensorFlow and Keras to recognize handwritten digits from the classic MNIST dataset.

## 📝 Overview

This project demonstrates how to use a basic feedforward neural network (Multi-Layer Perceptron) to classify handwritten digits (0-9) using the MNIST dataset. The dataset contains 60,000 training images and 10,000 test images of 28x28 grayscale digits.

## 🔍 Project Structure

- **Importing Libraries:** Essential packages like TensorFlow, Keras, NumPy, and Matplotlib.
- **Data Preprocessing:** Normalization and reshaping of MNIST data.
- **Model Architecture:**
  - `Flatten` layer to reshape 2D images into 1D vectors.
  - `Dense` hidden layer with ReLU activation (128 neurons).
  - `Dense` output layer with softmax activation (10 neurons).
- **Training the Model:** Using `categorical_crossentropy` loss and `adam` optimizer.
- **Evaluation:** Testing accuracy and loss on test data.
- **Visualization:** Displaying some test predictions and performance metrics.

## 🚀 Tech Stack

- Python 🐍
- TensorFlow
- Keras
- NumPy
- Matplotlib

## 🧠 Model Summary

- Input Layer: 784 neurons (flattened from 28x28)
- Hidden Layer: 128 neurons, ReLU activation
- Output Layer: 10 neurons, Softmax activation

## 🎯 Accuracy

Achieved around **97-98%** test accuracy in most runs.

## 📸 Sample Prediction Visuals

The notebook includes a visualization of predicted vs actual labels for a few test digits to give a better sense of model performance.

## 💡 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mnist-digit-classifier.git
   cd mnist-digit-classifier
2. Install the required libraries:

```bash
pip install -r requirements.txt
```
3. Run the notebook:

````bash
jupyter notebook mnist-dataset.ipynb
````

## ✅ To-Do / Future Improvements
Add dropout to reduce overfitting.

Try CNNs for better performance.

Add confusion matrix & classification report.

Deploy the model with a web UI (e.g., using Flask or Streamlit).

## Author
Muskan Tariq (aka ai_enthusiast86)

- **Instagram**: [ai_enthusiast86](https://www.instagram.com/ai_enthusiast86)
- **LinkedIn**: [Muskan Tariq](https://www.linkedin.com/in/muskan-tariq-095a50282)
- **Email:** [Muskan Tariq](muskantariq2003@gmail.com)

⭐ Don’t forget to star the repo if you found it helpful!
---

Let me know if you want it turned into a downloadable `.md` file too, or if you want a `requirements.txt` alongside! 💻🔥  
Alsoooo if you plan to push this to your GitHub, I can help you write a cool commit message or pinned post too 😎
