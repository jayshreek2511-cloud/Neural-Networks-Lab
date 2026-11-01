# Neural Networks – Practical Implementations

## About This Repository

This repository contains three practical assignments based on Artificial Neural Networks (ANNs) and Multi-Layer Perceptrons (MLPs).

The programs progress from understanding a basic artificial neuron to implementing, training, and optimizing neural networks using Python and NumPy.

Each section includes the assignment question, implementation details, and learning objectives.

---

## 1. Basic Neuron and Activation Functions

Implement a basic artificial neuron using inputs, weights, and bias. Visualize different activation functions and their derivatives, and investigate how they influence gradient flow.

### Implementation

- Implemented an artificial neuron using NumPy.
- Visualized Sigmoid, Tanh, ReLU, Leaky ReLU, GELU, and SiLU.
- Plotted the derivatives of these activation functions.
- Studied their behaviour and gradient flow.

**Notebook:** `01_Basic_Neuron_and_Activation_Functions.ipynb`

---

## 2. Multi-Layer Perceptron (MLP) with Backpropagation

Implement a single-layer perceptron and demonstrate its limitations using the XOR problem. Build an MLP from scratch using NumPy, implement forward propagation and backpropagation, verify gradients numerically, compare weight initialization methods, and train the network on a subset of Fashion-MNIST.

### Implementation

- Implemented a single-layer perceptron.
- Demonstrated why a single-layer perceptron cannot solve XOR.
- Built an MLP using NumPy to solve XOR.
- Implemented forward propagation and backpropagation.
- Verified gradients using numerical gradient checking.
- Compared different weight initialization methods.
- Applied the MLP to Fashion-MNIST classification.

**Notebook:** `02_MLP_with_Backpropagation.ipynb`

---

## 3. Optimization, Learning-Rate Scheduling, and Regularization

Demonstrate Batch, Stochastic, and Mini-batch Gradient Descent. Compare momentum-based and adaptive optimizers with constant and scheduled learning rates using Fashion-MNIST. Investigate overfitting and evaluate dropout, L2 regularization, data augmentation, early stopping, and plain versus residual MLP architectures.

### Implementation

- Compared Batch, Stochastic, and Mini-batch Gradient Descent.
- Implemented and compared SGD, Momentum, RMSProp, and Adam.
- Compared constant, step, and exponential learning-rate schedules.
- Investigated overfitting using training and validation curves.
- Implemented Dropout and L2 regularization.
- Applied data augmentation and early stopping.
- Compared Plain MLP and Residual MLP architectures.

**Notebook:** `03_Optimization_Learning_Rate_Scheduling_and_Regularization.ipynb`

---

## Technologies Used

- **Python** – Programming language
- **NumPy** – Neural network implementation and mathematical operations
- **Pandas** – Data handling and result comparison
- **Matplotlib** – Graphs and visualizations
- **TensorFlow/Keras** – Fashion-MNIST dataset
- **Kaggle Notebooks / Jupyter Notebook** – Development environment

---

## Learning Outcomes

Through these three assignments, students gain practical experience with:

- Artificial neurons and activation functions.
- Perceptrons and Multi-Layer Perceptrons.
- Forward propagation and backpropagation.
- Gradient calculation and weight initialization.
- Optimization algorithms and learning-rate scheduling.
- Overfitting and regularization techniques.
- Neural network training and image classification.
- Residual connections and model comparison.

---

## Conclusion

These assignments provide a step-by-step understanding of neural networks, starting from the fundamentals of an artificial neuron and progressing towards training and optimizing MLP architectures.

The focus is on implementing concepts from scratch, experimenting with different techniques, visualizing results, and understanding how neural networks learn and improve their performance.
