# Artificial Neural Networks (ANN) Implementation

A comprehensive implementation of Artificial Neural Networks designed to solve complex non-linear problems through supervised learning. This project demonstrates the core mechanics of deep learning, from forward propagation to gradient descent.

## 🚀 Key Features

* **Multi-Layer Perceptron (MLP):** Robust architecture featuring input, hidden, and output layers.
* **Backpropagation:** Optimized learning using the Chain Rule to minimize loss.
* **Activation Functions:** Implementation of `ReLU`, `Sigmoid`, and `Softmax`.
* **Optimization:** Support for Stochastic Gradient Descent (SGD) and Adam optimizer.

## 🏗️ Architecture

The model processes data through a structured pipeline:

1.  **Input Layer:** Receives raw features.
2.  **Hidden Layers:** Extracts deep patterns using weights ($w$) and biases ($b$).
3.  **Output Layer:** Provides final classification or regression results.

The fundamental transformation at each neuron is represented as:
$$z = \sum (w_i \cdot x_i) + b$$
$$a = \sigma(z)$$

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** NumPy, Pandas, Scikit-Learn
* **Tools:** Git, Jupyter Notebooks

## 📈 Getting Started

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/your-username/ann-project.git](https://github.com/your-username/ann-project.git)
   
2)Install dependencies:
pip install -r requirements.txt

3)Run the model:
python main.py
