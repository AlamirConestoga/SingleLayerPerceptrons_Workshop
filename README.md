# Single Layer Perceptrons Workshop

## Project Overview

This project was completed as part of the Foundations of Machine Learning Frameworks course at Conestoga College.

The workshop explores the fundamentals of Artificial Neural Networks (ANNs), including how artificial neurons process inputs, apply weights and biases, and use activation functions to generate predictions.

We worked as a group to complete the workshop activities, implement the coding challenges, and understand how gradient descent and backpropagation help neural networks learn.

## Workshop Objectives

The main objectives of this workshop are:

- Understand the relationship between biological neurons and artificial neurons.
- Explore five activation functions: Identity, Binary Step, Sigmoid, Tanh, and ReLU.
- Implement single-layer perceptrons using PyTorch and TensorFlow.
- Demonstrate AND, OR, and inhibitory logic gates.
- Understand weighted sums, biases, and activation functions.
- Implement ANN prediction examples and coding challenges.
- Understand loss calculation, gradient descent, and backpropagation.

## Workshop Activities

### 1. ANN Foundations and Activation Functions

We studied how artificial neurons are inspired by biological neurons.

An artificial neuron calculates a weighted sum of its inputs, adds a bias, and applies an activation function.

We explored and visualized five activation functions using NumPy and Matplotlib:

- Identity
- Binary Step
- Sigmoid
- Tanh
- ReLU

### 2. Single-Layer Perceptron Logic

We implemented perceptron models for the following logic cases:

- C = A
- AND gate
- OR gate
- Inhibitory logic: A AND NOT B

We tested all required binary input combinations and compared the results using PyTorch and TensorFlow.

### 3. Canada's Wonderland ANN Example

We explored a single-neuron prediction example to decide whether to visit Canada's Wonderland.

The model uses three inputs:

- Weather
- Ticket queue
- Health

We calculated the weighted sum, applied sigmoid activation, and examined the prediction and error.

### 4. Movie Decision Perceptron Challenge

We implemented a single-layer perceptron to predict whether to go to the movies.

The model considers three binary inputs:

- Weather
- Company
- Proximity to the theatre

We selected weights and a bias, applied the binary step activation function, and tested all eight possible input combinations.

### 5. Prostate Cancer ANN Prediction Challenge

We implemented the prostate cancer prediction example based on the Deep Learning Fundamentals class slides.

The model uses PSA as its input, calculates a weighted sum, and applies the sigmoid activation function.

We also demonstrated:

- Prediction interpretation using a threshold of 0.5.
- Squared-error loss calculation using an assumed training label.
- Gradient calculation using PyTorch autograd.
- Weight and bias updates using gradient descent.
- Comparison of predictions and loss before and after the update.

This example is for educational purposes and is not a clinically validated diagnostic model.

### 6. Gradient Descent and Backpropagation

We studied how neural networks learn by minimizing prediction errors.

The workshop demonstrates how gradients are calculated through backpropagation and how gradient descent updates weights and biases using a learning rate.

We also explored training results and visualizations showing changes in the model parameters and loss.

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Matplotlib
- PyTorch
- TensorFlow

## Project Structure

```text
SingleLayerPerceptrons_Workshop/
│
├── SingleLayerPerceptrons_Workshop.ipynb
├── MinimalSingleSayerPerceptronTrainingLoop.py
├── README.md
├── requirements.txt
└── images/
    └── Workshop diagrams and illustrations
```

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/AlamirConestoga/SingleLayerPerceptrons_Workshop.git
   ```

2. Navigate to the project folder:

   ```bash
   cd SingleLayerPerceptrons_Workshop
   ```

3. Install the required libraries:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Open `SingleLayerPerceptrons_Workshop.ipynb` in VS Code or Jupyter Notebook.

5. Select a Python environment containing the required libraries.

6. Run the notebook cells in order and review the predictions, explanations, and visualizations.

The `images` folder and training-loop Python script must remain in the project folder for the notebook to work correctly.

## GitHub Repository

https://github.com/AlamirConestoga/SingleLayerPerceptrons_Workshop

## Conclusion

Through this workshop, we learned how a single artificial neuron makes predictions using inputs, weights, bias, and activation functions.

The logic gate examples helped us understand how perceptrons make binary decisions. The movie and prostate cancer challenges allowed us to apply these concepts to prediction problems.

We also learned how gradient descent and backpropagation are used to adjust model parameters and reduce prediction errors.

Overall, this workshop helped us build a foundation for understanding artificial neural networks and their training process.