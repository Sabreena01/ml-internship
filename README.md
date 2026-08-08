# ml-internship
Machine Learning Internship Tasks and Projects
#  Machine Learning Internship

Welcome to my Machine Learning Internship repository.

##  About

This repository contains all the assignments, notebooks, projects, and learning completed during my AI & Machine Learning Internship.

##  Internship Progress

### Day 1
- ✅ Installed Ubuntu (WSL)
- ✅ Installed Miniconda
- ✅ Created Conda Environment
- ✅ Installed NumPy
- ✅ Installed Pandas
- ✅ Installed Matplotlib
- ✅ Installed Scikit-learn
- ✅ Installed Jupyter
- ✅ Learned Linux Command Line Basics

---

##  Technologies

- Python
- Linux
- Git & GitHub
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---
## DAILY TASKS

## Task 01 - Exploring the Iris Dataset

### Objective

Learn the basics of working with a Machine Learning dataset by exploring the Iris dataset using Python, Pandas, Matplotlib, and Scikit-learn.

### Tasks Completed

* Loaded the Iris dataset from Scikit-learn
* Explored the dataset structure and dimensions
* Viewed feature names and target labels
* Converted the dataset into a Pandas DataFrame
* Examined the first few rows of the dataset
* Checked dataset information and summary statistics
* Identified different Iris flower species
* Visualized the dataset using plots to understand feature distributions
* Learned how features relate to different flower classes

### Key Learning

This exercise introduced me to one of the most popular datasets in Machine Learning. I learned how to load, inspect, and visualize a dataset, understand its features and labels, and perform basic exploratory data analysis (EDA). These skills form the foundation for building Machine Learning models.


## Task 02 - Exploring the Digits Dataset

### Objective

The objective of this exercise was to understand how images are represented as numerical arrays and to perform basic image processing operations using NumPy and Matplotlib. This hands-on activity also introduced important concepts that serve as the foundation for computer vision and deep learning.

### Tasks Completed

* Loaded the built-in Digits dataset using `sklearn.datasets.load_digits()`
* Explored the dataset structure, including:

  * Total number of images
  * Image dimensions (8 × 8 pixels)
  * Number of target labels
* Examined a handwritten digit as a raw NumPy array to understand pixel values
* Learned that pixel intensity values range from **0 (black)** to **16 (brightest)**
* Visualized multiple handwritten digit images with their corresponding labels using Matplotlib
* Performed image manipulation using NumPy:

  * Cropped an image using array slicing
  * Flipped images horizontally
  * Flipped images vertically
  * Modified images by setting selected pixel values to zero
* Plotted histograms to analyze the distribution of pixel intensity values in different images
* Computed and visualized the average handwritten image for each digit (0–9) using NumPy's `mean()` function
* Added Markdown documentation throughout the notebook to explain every step and improve readability

### Key Learning

This exercise helped me understand that digital images are simply matrices of numerical pixel values. I learned how NumPy can be used to manipulate image data, how Matplotlib helps visualize images and pixel distributions, and how averaging multiple images reveals common patterns within a dataset. These concepts are fundamental for image processing, computer vision, and deep learning applications.


##  Task 03 - Neural Networks with the Digits Dataset

###  Objective
Learn the basics of neural networks using the Scikit-learn Digits dataset and compare the performance of Logistic Regression and Multi-Layer Perceptron (MLP) models.

###  Topics Covered
- Understanding Neural Networks
- Backpropagation and Gradient Descent
- Logistic Regression
- Multi-Layer Perceptron (MLP)
- Hidden Layers and Neurons
- Model Evaluation
- Overfitting
- Loss Curve Analysis

###  Tasks Completed
- Trained a Logistic Regression model as a baseline classifier.
- Built an MLP Classifier with one hidden layer containing 32 neurons.
- Compared the training and testing accuracy of Logistic Regression and MLP.
- Experimented with different hidden layer configurations:
  - 8 neurons
  - 32 neurons
  - 128 neurons
  - Two hidden layers (64, 32)
- Created a comparison table for different network architectures.
- Plotted and analyzed the training loss curves.
- Connected the loss curve with the concepts of Gradient Descent and Backpropagation.
- Documented observations and conclusions in Markdown.

###  Key Results

| Model | Training Accuracy | Testing Accuracy |
|--------|------------------:|-----------------:|
| Logistic Regression | 100.00% | 97.50% |
| MLP (32 neurons) | 100.00% | 97.78% |

###  Hidden Layer Experiment

| Hidden Layer | Training Accuracy | Testing Accuracy |
|--------------|------------------:|-----------------:|
| 8 | 100.00% | 94.44% |
| 32 | 100.00% | 97.78% |
| 128 | 100.00% | 97.78% |
| (64, 32) | 100.00% | 96.67% |

###  Key Observations
- Both Logistic Regression and MLP achieved perfect training accuracy.
- The MLP model performed slightly better than Logistic Regression on the test dataset.
- Increasing the number of neurons improved performance up to a point, but larger networks did not always result in higher testing accuracy.
- The loss curve showed a steady decrease during training, demonstrating how Gradient Descent and Backpropagation optimize the neural network.
- This experiment reinforced the idea that a more complex model does not always generalize better on unseen data.

 
# task 04 - MNIST Handwritten Digit Classification using MLP

## Overview

On Day 04, I worked with the **MNIST Handwritten Digits** dataset and implemented a **Multi-Layer Perceptron (MLP) Classifier** using Scikit-learn. The objective was to understand the importance of preprocessing, compare model performance with and without feature scaling, and evaluate the classifier using different performance metrics.

---

## Tasks Completed

- Loaded the MNIST dataset using `fetch_openml()`.
- Explored dataset shape and structure.
- Visualized handwritten digit images.
- Scaled pixel values from **0–255** to **0–1**.
- Trained an MLP classifier on both unscaled and scaled datasets.
- Compared training time and testing accuracy.
- Evaluated the model using a confusion matrix.
- Visualized misclassified images.
- Documented observations and final analysis.

---

## Results

| Model | Training Time | Test Accuracy |
|-------|--------------:|--------------:|
| MLP (Without Scaling) | 10.95 s | 92.52% |
| MLP (With Scaling) | 11.49 s | 96.23% |

---

## Key Learning

- Feature scaling significantly improved model performance.
- Larger datasets require more computation and longer training time.
- Confusion matrices and misclassified samples help analyze model performance beyond overall accuracy.
- MLP classifiers perform well on image classification tasks after proper preprocessing.

---


---

**Status:** ✅ Completed

## Skills Practiced

- Python
- NumPy
- Matplotlib
- Scikit-learn
- Neural Networks
- Multi-Layer Perceptron (MLP)
- Feature Scaling
- Model Evaluation

# Task 05 — Simple Neural Network Demonstration

## Overview

This task focused on understanding the basic structure and working of a **Neural Network** through a simple implementation.

The objective was to move from the Machine Learning concepts covered in the previous tasks toward understanding how neural networks process input data and produce predictions.

This task provided a practical introduction to neural-network architecture, layers, weights, biases, activation functions, forward propagation, and model output.

---

## Task Objective

The main objectives of this task were:

* Understand the basic architecture of a neural network.
* Understand how data flows through different layers.
* Learn the role of weights and biases.
* Understand activation functions.
* Perform forward propagation.
* Observe how a neural network transforms input data into an output.
* Connect the theoretical concepts of neural networks with a practical implementation.

---

## Work Completed

During this task, I created and explored a simple neural-network demonstration.

The work included:

1. Preparing input data for the neural network.
2. Defining the neural-network structure.
3. Creating input, hidden, and output layers.
4. Initializing weights and biases.
5. Passing input values through the network.
6. Applying activation functions.
7. Performing forward propagation.
8. Generating and observing the final output.
9. Understanding how changes in network parameters affect the output.

---

## Approach

The neural network was studied using a layer-by-layer approach.

### Input Layer

The input layer receives the numerical features provided to the model.

### Hidden Layer

The hidden layer processes the input values using weights and biases.

Each neuron calculates a weighted combination of its inputs and then applies an activation function.

### Output Layer

The output layer receives the processed information from the hidden layer and produces the final model output.

The overall flow can be represented as:

```text
Input Data
    ↓
Input Layer
    ↓
Hidden Layer
    ↓
Activation Function
    ↓
Output Layer
    ↓
Prediction / Output
```

---

## Key Concepts Learned

### 1. Neural Network Architecture

A neural network is composed of interconnected layers of neurons. The basic structure includes an input layer, hidden layer(s), and output layer.

### 2. Weights

Weights determine the importance of different input features. During model learning, these values are adjusted to improve the predictions.

### 3. Bias

A bias provides an additional parameter that allows a neuron to shift its output and improves the flexibility of the model.

### 4. Activation Functions

Activation functions introduce non-linearity into the network. Without activation functions, a neural network would behave largely like a linear model regardless of the number of layers.

### 5. Forward Propagation

Forward propagation is the process of passing input data through the network layer by layer until the final output is generated.

### 6. Model Output

The final layer produces the output based on the information processed by the previous layers.

---

## Technologies Used

* **Python**
* **Jupyter Notebook**
* **NumPy**
* Neural Network concepts and mathematical operations

---

## Learning Outcomes

After completing this task, I gained a better understanding of:

* Basic neural-network architecture.
* How neurons process numerical inputs.
* The role of weights and biases.
* How activation functions transform neuron outputs.
* How information moves through a neural network.
* How forward propagation produces a prediction.
* The connection between mathematical operations and practical neural-network implementation.

---

## What I Learned from This Task

This task helped me move beyond traditional Machine Learning models and understand the basic principles behind **Artificial Neural Networks**.

I learned that a neural network is not simply a predefined prediction system. Its output is produced through a sequence of mathematical operations involving inputs, weights, biases, activation functions, and multiple layers.

This understanding provided the foundation for the next task, where I explored the neural-network calculations manually.

---

## Notebook

`simple_neural_network_demo.ipynb`

---

## Summary

**Task 05 introduced the practical structure and workflow of a simple neural network, providing the foundation for understanding how neural networks process data and generate outputs.**


# Task 06 — Manual Neural Network Forward Pass

## Overview

This task focused on understanding the **mathematical operations performed inside a neural network** by implementing a forward pass manually.

Instead of relying entirely on a neural-network framework, the calculations were broken down step by step to understand how inputs are transformed into outputs through weights, biases, activation functions, and layers.

This task built upon the concepts introduced in Task 05 and provided a deeper understanding of what happens inside a neural network during prediction.

---

## Task Objective

The main objectives of this task were:

* Understand the mathematical working of a neural network.
* Manually calculate neuron outputs.
* Understand the relationship between inputs, weights, and biases.
* Apply activation functions manually.
* Understand forward propagation step by step.
* Observe how information moves from one layer to another.
* Understand how the final prediction is generated.

---

## Work Completed

In this task, I implemented a **manual neural-network forward pass** using numerical calculations.

The work included:

1. Defining input values.
2. Defining weights for the neural-network connections.
3. Defining biases for the neurons.
4. Calculating weighted sums.
5. Adding the corresponding biases.
6. Applying activation functions.
7. Passing the resulting values to the next layer.
8. Repeating the process for subsequent layers.
9. Calculating the final output of the network.
10. Observing how the network transforms the original input into the final prediction.

---

## Approach

The forward pass was implemented layer by layer.

The general process followed was:

```text
Input
  ↓
Weighted Sum
  ↓
Add Bias
  ↓
Activation Function
  ↓
Next Layer
  ↓
Weighted Sum
  ↓
Add Bias
  ↓
Activation Function
  ↓
Final Output
```

For a neuron, the basic calculation can be represented as:

```text
z = (input × weight) + bias
```

For multiple inputs, the weighted sum becomes the combination of all input-weight products plus the bias.

The activation function is then applied to this value before passing the result to the next layer.

---

## Main Concepts Studied

### 1. Inputs

Inputs are the numerical values provided to the neural network.

These values form the starting point of the forward-propagation process.

---

### 2. Weights

Each connection between neurons has an associated weight.

Weights determine how strongly each input contributes to the neuron's output.

For example:

```text
Input × Weight
```

contributes to the neuron's weighted sum.

---

### 3. Bias

A bias is added to the weighted sum before applying the activation function.

It allows the neuron to shift its activation and provides additional flexibility to the model.

---

### 4. Weighted Sum

The neuron first calculates the weighted combination of its inputs.

For multiple inputs:

```text
z = x₁w₁ + x₂w₂ + ... + xₙwₙ + b
```

where:

* `x` = input
* `w` = weight
* `b` = bias
* `z` = weighted sum before activation

---

### 5. Activation Function

After calculating the weighted sum, an activation function is applied.

The activation transforms the value before it is passed to the next layer.

This is important because activation functions introduce **non-linearity**, allowing neural networks to learn complex patterns.

---

### 6. Forward Propagation

Forward propagation is the complete process of moving information from the input layer through the hidden layers to the output layer.

No parameter updates occur during a basic forward pass; the purpose here is to calculate the network's output from the given inputs and parameters.

---

## Technologies Used

* **Python**
* **Jupyter Notebook**
* **NumPy**
* Mathematical operations for neural-network calculations

---

## Practical Learning

One of the main goals of this task was to avoid treating the neural network as a black box.

By calculating the forward pass manually, I was able to understand:

* How each input contributes to a neuron.
* How weights influence the contribution of each input.
* How biases modify neuron outputs.
* How activation functions transform the calculated values.
* How the output of one layer becomes the input to the next layer.
* How the final output is obtained from a sequence of calculations.

---

## What I Learned from This Task

This task gave me a deeper understanding of the internal mathematical working of neural networks.

Previously, a neural network could be viewed simply as a model that receives input and produces an output. Through the manual forward-pass implementation, I learned that the prediction is actually the result of a sequence of mathematical operations performed across multiple neurons and layers.

It helped me connect the **theory of neural networks with the actual calculations performed by the model**.

---

## Connection with Task 05

Task 05 introduced the **structure and workflow of a simple neural network**.

Task 06 went one step deeper by manually calculating what happens **inside the network during forward propagation**.

Therefore, the progression was:

```text
Task 05
Simple Neural Network
        ↓
Understand Architecture
        ↓
Task 06
Manual Forward Pass
        ↓
Understand Internal Calculations
```

---

## Learning Outcomes

After completing this task, I developed a stronger understanding of:

* Neural-network forward propagation.
* Weighted sums.
* Bias terms.
* Activation functions.
* Layer-to-layer information flow.
* Mathematical operations behind predictions.
* The relationship between neural-network theory and implementation.

---

## Notebook

`manual_neural_network_forward_pass.ipynb`

---

## Summary

**Task 06 provided a detailed mathematical understanding of how a neural network performs forward propagation by manually calculating the operations involved in generating an output.**



##  Author

**Sabreena Rashid**

GitHub: https://github.com/sabreena01
