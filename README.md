# ANN-Based Membrane Fouling Risk Prediction

**Domain:** Water Treatment & Desalination | **Lab Experiment 2**

## 📌 Overview

This project implements an Artificial Neural Network (ANN) from scratch using NumPy to classify membrane fouling risk in a simulated Reverse Osmosis (RO) plant. It uses backpropagation and gradient descent to learn patterns from synthetic operational data and classify fouling risk as **Low or High**.

## ⚙️ Features

* Synthetic dataset generation with 7 RO plant parameters.
* ANN implementation using forward propagation and backpropagation.
* Comparison of **Sigmoid, Tanh, and ReLU** activation functions.
* Model evaluation using accuracy, confusion matrix, precision, recall, and F1-score.
* Training-loss visualization and activation-function comparison.
* Sample prediction using new simulated plant readings.

## 🛠️ Tech Stack

Python | NumPy | Pandas | Matplotlib | Scikit-learn

## 🚀 Getting Started

Install the dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn
```

Run the script:

```bash
python ann_fouling_prediction.py
```

## 📊 Outputs

* `osmof_loss_comparison.png` — Training loss comparison.
* `osmof_activation_comparison.png` — Training and testing accuracy comparison.
* Classification report and sample fouling-risk prediction.

## ⚠️ Disclaimer

This project uses **synthetic data and simulated fouling labels** for educational purposes. It is not based on actual Osmoflo operational data and is not validated for real-world industrial use.

## 👩‍💻 Author

**Komal Pawar** | MSc Data Science | Machine Learning & Data Analytics

