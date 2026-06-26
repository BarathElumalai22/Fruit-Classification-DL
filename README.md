# 🍎 Fruit Classification Using Deep Learning

## 📌 Overview

This project implements a **Deep Learning-based multiclass classification model** using **TensorFlow** and **Keras** to classify fruits based on their physical characteristics.

The model predicts the fruit category from four numerical features:

* Weight (g)
* Diameter (cm)
* Sweetness
* Firmness

---

## 📂 Dataset

**Type:** Supervised Machine Learning Dataset

**Problem:** Multiclass Classification

### Features

| Feature     | Description                  |
| ----------- | ---------------------------- |
| weight_g    | Weight of the fruit in grams |
| diameter_cm | Diameter in centimeters      |
| sweetness   | Sweetness score              |
| firmness    | Firmness score               |

### Target

| Target |
| ------ |
| fruit  |

Classes:

* Apple
* Banana
* Orange
* Mango

---

## 🛠 Technologies Used

* Python
* TensorFlow
* Keras
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## 🔄 Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Label encode the target column
5. Split the dataset into training and testing sets
6. Standardize the feature values
7. Build a Sequential Deep Learning model
8. Train the model
9. Evaluate model performance
10. Predict fruit classes for unseen data

---

## 🧠 Deep Learning Architecture

* Input Layer: 4 Features
* Hidden Layer 1: Dense (25 neurons, ReLU)
* Hidden Layer 2: Dense (35 neurons, ReLU)
* Hidden Layer 3: Dense (45 neurons, ReLU)
* Output Layer: Dense (4 neurons, Softmax)

Optimizer:

* Adam

Loss Function:

* Sparse Categorical Crossentropy

Evaluation Metric:

* Accuracy
