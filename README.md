# Hyperparameter Tuning in Artificial Neural Networks (ANN)

## 1. Introduction
This repository demonstrates **hyperparameter tuning** in Artificial Neural Networks (ANNs). Hyperparameter tuning is crucial to improve model performance by selecting the optimal combination of parameters like learning rate, optimizer, number of layers, activation functions, and more.

---

## 2. Different Hyperparameters in ANN
The project explores key hyperparameters including:
- **Architecture Hyperparameters:** Number of hidden layers, hidden units, activation functions.  
- **Learning Hyperparameters:** Learning rate, optimizers.  
- **Regularization Hyperparameters:** Dropout rate, L1/L2 regularization.  
- **Training Hyperparameters:** Batch size, number of epochs.  

---

## 3. Hyperparameter Tuning with Different Optimizers
This section experiments with multiple optimizers to evaluate their effect on model performance, such as:
- SGD  
- SGD with Momentum  
- Nesterov Accelerated Gradient (NAG)  
- Adagrad  
- RMSprop  
- Adam  

---

## 4. Hyperparameter Tuning with Different Number of Hidden Layers, Hidden Units, and Learning Rate
Experiments include:
- Varying the **number of hidden layers**.  
- Changing the **number of neurons per layer**.  
- Adjusting the **learning rate** to find optimal convergence.  

---

## 5. Hyperparameter Tuning with Different Activation Functions
Tests the impact of different activation functions on ANN performance:
- Sigmoid  
- Tanh  
- ReLU  
- Leaky ReLU  
- Parametric ReLU (PReLU)  
- ELU  
- SELU  
- Softmax  

---

## 6. All-in-One Hyperparameter Tuning
Combines all the above hyperparameters (optimizers, hidden layers, units, learning rate, activation functions) in a **comprehensive tuning pipeline** to identify the best configuration.  

---

## 7. Try Hyperparameter Tuning with Different Epochs
Investigates the effect of varying the **number of training epochs** on the model's performance and convergence behavior.

---

## Usage
1. Clone this repository:  
```bash
git https://github.com/gandlanandhu/sample-hyperparameter-tuning.git

