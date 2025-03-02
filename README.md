# Hyperparameter Optimization for Multi-Layer Perceptron (MLP)

## Overview

This repository contains the implementation of Part B and the Bonus Exercise from the second Take-Home Assignment (THA2) for the **Intelligent Systems - Machine Learning (IS-ML)** course at the University of Luxembourg. The assignment focuses on **Hyperparameter Optimization** and **Regularization** for a Multi-Layer Perceptron (MLP) model, implemented from scratch using Python and auxiliary libraries.

## Assignment Details

### Part B: Hyperparameter Optimization

The goal of this part is to optimize the hyperparameters of an MLP model trained for binary classification. The tasks include:

1. **Parameter Initialization:**
   - Comparing the performance of a model with zero-initialized weights against a well-initialized model.
2. **Learning Rate vs. Parameter Initialization:**
   - Evaluating different learning rates and initialization strategies using a heatmap.
3. **Activations Visualization:**
   - Visualizing hidden layer activations for the best and worst performing models.
4. **Comprehensive Hyperparameter Tuning:**
   - Exploring different model architectures and hyperparameters using a **Parallel Coordinates Plot**.

### Bonus Exercise: Regularization

An additional experiment was conducted by applying **L1** and **L2** regularization techniques to the optimized MLP model. The evaluation includes:

- Measuring classification accuracy and analyzing confusion matrices.
- Examining the effect of regularization on weight magnitudes and sparsity (number of weights reduced to zero).

## Dataset

The model is trained and validated on the dataset provided in the assignment, consisting of two files:

- `THA2train.xlsx`: Training dataset
- `THA2validate.xlsx`: Validation dataset

Each row in the dataset represents a data point with:

- **Features:** Two numerical input features (`x0`, `x1`).
- **Label:** A binary class label (`0` or `1`).

## Implementation Details

The MLP model is implemented from scratch without using deep learning libraries such as TensorFlow or PyTorch. The following libraries were used for auxiliary tasks:

- **NumPy** (for numerical computations)
- **Matplotlib & Seaborn** (for visualization)
- **Pandas** (for data handling)

## Results

- The optimized model achieves **high classification accuracy** on the validation set after tuning hyperparameters.
- The **heatmap analysis** reveals the impact of different learning rates and initialization strategies.
- The **parallel coordinates plot** provides insights into how various hyperparameters influence model performance.
- **L1 and L2 regularization** demonstrate different effects on weight sparsity and generalization.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/PraveenAgnihotry/Hyperparameter_Optimization_for_MLP_Network.git
   ```
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```
3. Run the training script:
   ```bash
   python mlp_hyperparameter_optimization.py
   ```
4. View the results in the generated plots and logs.

## Author

Praveen Agnihotry

## License

This project is for academic purposes and follows the guidelines set by the **University of Luxembourg**.

