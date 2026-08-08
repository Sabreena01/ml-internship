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
# Task 01 — Iris Dataset Analysis

## Overview

This task focused on exploring and understanding a Machine Learning dataset through **Exploratory Data Analysis (EDA)**.

The **Iris dataset** was used as the first practical dataset for learning how to load, inspect, analyze, summarize, and visualize data using Python and common Machine Learning libraries.

The task provided a foundation for understanding how raw dataset information is explored before applying Machine Learning algorithms.

---

## Task Objective

The main objectives of this task were:

* Understand the structure of a Machine Learning dataset.
* Load a built-in dataset using Scikit-learn.
* Convert the dataset into a Pandas DataFrame.
* Explore features and target labels.
* Inspect the dataset dimensions and data types.
* Generate descriptive statistics.
* Identify the different target classes.
* Analyze feature distributions.
* Visualize relationships between features.
* Understand the importance of Exploratory Data Analysis before model building.

---

## Dataset

The **Iris dataset** is a well-known dataset commonly used for introductory Machine Learning and classification tasks.

It contains measurements of Iris flowers belonging to three different species:

* **Setosa**
* **Versicolor**
* **Virginica**

The dataset contains four numerical features:

| Feature      | Description         |
| ------------ | ------------------- |
| Sepal Length | Length of the sepal |
| Sepal Width  | Width of the sepal  |
| Petal Length | Length of the petal |
| Petal Width  | Width of the petal  |

The target variable represents the Iris species.

---

## Work Completed

### 1. Dataset Loading

The Iris dataset was loaded using **Scikit-learn**.

This provided a convenient way to access the dataset and begin the analysis.

---

### 2. Dataset Structure Exploration

The dataset was converted into a Pandas DataFrame and examined to understand:

* Number of rows and columns.
* Feature names.
* Target labels.
* Data types.
* Overall dataset structure.

This step helped establish what information was available before performing further analysis.

---

### 3. Initial Data Inspection

The first few records of the dataset were examined to understand how the data was organized.

The dataset was also checked for:

* Missing values.
* Data types.
* Feature information.
* Basic statistical properties.

---

### 4. Descriptive Statistics

Summary statistics were generated for the numerical features.

This helped understand the:

* Mean
* Standard deviation
* Minimum value
* Maximum value
* Quartiles

of the different measurements.

Descriptive statistics provide an initial understanding of the distribution and variation of the dataset.

---

### 5. Target/Class Analysis

The different Iris species were examined to understand the classification labels.

This helped identify how the observations were distributed across the three classes.

---

### 6. Data Visualization

Different visualizations were created to better understand the dataset.

The analysis focused on:

* Feature distributions.
* Relationships between features.
* Differences between Iris species.
* Patterns that could potentially help distinguish the classes.

Visualization made it easier to identify patterns that may not be obvious from numerical statistics alone.

---

## Exploratory Data Analysis Workflow

The overall workflow followed in this task was:

```text
Load Dataset
     ↓
Convert to DataFrame
     ↓
Inspect Dataset
     ↓
Check Structure & Data Types
     ↓
Generate Descriptive Statistics
     ↓
Analyze Target Classes
     ↓
Visualize Features
     ↓
Identify Patterns & Relationships
```

---

## Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**

---

## Key Concepts Learned

### Exploratory Data Analysis (EDA)

EDA is the process of understanding a dataset before applying Machine Learning algorithms.

It helps identify:

* Data structure.
* Feature characteristics.
* Missing or problematic values.
* Distributions.
* Relationships between variables.
* Potential patterns in the data.

---

### Features and Target

I learned the difference between:

**Features:**
The input variables used to describe each observation.

**Target:**
The output/class that a Machine Learning model may eventually learn to predict.

In this dataset, the flower measurements are the features, while the Iris species are the target classes.

---

### Data Visualization

Visualization provides a graphical representation of the dataset.

It helps identify patterns, differences between classes, and relationships between features more easily than looking at raw numbers alone.

---

## What I Learned

This task introduced me to the basic workflow of working with a Machine Learning dataset.

I learned how to:

* Load datasets using Scikit-learn.
* Work with Pandas DataFrames.
* Inspect and understand dataset structure.
* Analyze numerical features.
* Examine target classes.
* Generate summary statistics.
* Create visualizations using Matplotlib.
* Perform basic Exploratory Data Analysis.

Most importantly, I learned that **understanding and exploring the data is an important step before building a Machine Learning model**.

---

## Learning Outcome

By completing this task, I developed a foundation in **data exploration and preprocessing**, which is essential for later Machine Learning tasks.

The concepts learned here were used as a starting point for subsequent tasks involving classification models and neural networks.

---

## Notebook

`iris_analysis.ipynb`


---

## Summary

**Task 01 focused on understanding the Iris dataset through Exploratory Data Analysis. The task established the fundamental workflow of loading, inspecting, analyzing, and visualizing Machine Learning data before model development.**


# Task 02 — Digits Dataset Exploration

## Overview

This task focused on exploring the **Scikit-learn Digits dataset** and understanding how handwritten digit images are represented and manipulated using Python.

The main purpose was to move from basic tabular-data exploration toward **image-based data**, while learning how images can be represented as numerical arrays and analyzed using NumPy and Matplotlib.

---

## Task Objective

The objectives of this task were to:

* Load the built-in Digits dataset from Scikit-learn.
* Understand how images are represented as numerical arrays.
* Explore the structure and dimensions of the dataset.
* Visualize handwritten digit images.
* Analyze pixel intensity values.
* Manipulate image arrays using NumPy.
* Perform basic image transformations.
* Study pixel-value distributions using histograms.
* Calculate and visualize average images for each digit.

---

## Dataset

The **Scikit-learn Digits dataset** contains handwritten digit images representing the numbers **0–9**.

The dataset contains:

* **1,797 images**
* **10 classes** — digits 0 through 9
* Each image has a resolution of **8 × 8 pixels**
* Each image contains **64 pixel features**
* Pixel intensity values range from **0 to 16**

The dataset therefore provides both:

* A flattened representation: `1797 × 64`
* An image representation: `1797 × 8 × 8`

These properties were explored directly in the notebook.

---

## Work Completed

### 1. Loading the Dataset

The Digits dataset was loaded using:

```python
from sklearn.datasets import load_digits
```

The dataset object was examined to understand its available data, images, targets, and feature information.

---

### 2. Exploring Dataset Dimensions

The dataset dimensions were inspected.

The results showed:

```text
Data shape    : (1797, 64)
Images shape  : (1797, 8, 8)
Target shape  : (1797,)
```

This helped establish the relationship between an image and its numerical representation.

---

### 3. Understanding Images as Arrays

Individual digit images were examined as NumPy arrays.

Each value represents the intensity of a pixel:

* Values close to **0** represent darker pixels.
* Higher values represent brighter pixels.

This demonstrated that a digital image can be treated as a matrix of numerical values.

---

### 4. Visualizing Sample Images

Multiple handwritten digit images were displayed using Matplotlib together with their corresponding labels.

This helped connect the numerical representation of an image with its actual visual appearance.

---

### 5. Image Manipulation

NumPy slicing was used to manipulate image arrays.

The notebook explored operations such as:

* Cropping an image.
* Horizontal flipping.
* Vertical flipping.
* Modifying selected pixel regions.
* Setting selected pixel values to zero.

These exercises demonstrated that basic image transformations can be performed directly through array operations.

---

### 6. Pixel Value Histograms

Histograms of pixel values were generated to understand the distribution of intensity values within digit images.

This helped visualize:

* Frequency of dark pixels.
* Frequency of brighter pixels.
* Overall pixel-intensity distribution.

The notebook observed that many pixels are close to zero because the background of the digit images is predominantly dark.

---

### 7. Average Image for Each Digit

Average images were calculated for each digit from **0 to 9**.

For each class:

1. Images belonging to the digit were selected.
2. Mean pixel values were calculated.
3. The resulting average image was visualized.

The average images appeared somewhat blurred because they represent multiple handwriting styles for the same digit.

---

## Approach

The overall workflow was:

```text
Load Digits Dataset
        ↓
Inspect Dataset Structure
        ↓
Understand Image Arrays
        ↓
Visualize Sample Images
        ↓
Manipulate Image Arrays
        ↓
Analyze Pixel Distributions
        ↓
Calculate Average Digit Images
        ↓
Interpret Observations
```

---

## Technologies Used

* **Python**
* **Jupyter Notebook**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**

---

## Key Concepts Learned

### Image Representation

I learned that an image can be represented as a matrix of numerical pixel values.

### Pixel Intensity

Pixel values represent the brightness information of an image.

### NumPy Array Manipulation

NumPy slicing can be used to crop, flip, modify, and transform image data.

### Data Visualization

Matplotlib can be used to visualize both images and numerical distributions.

### Class-Based Analysis

Grouping images by their target digit makes it possible to calculate representative statistics such as average images.

---

## Learning Outcomes

After completing this task, I gained practical experience in:

* Working with image datasets.
* Understanding image dimensions and pixel representations.
* Manipulating images as NumPy arrays.
* Visualizing image data.
* Analyzing pixel distributions.
* Computing class-level statistics.
* Preparing image data for future Machine Learning tasks.

---

## Connection to the Next Task

Task 02 focused on **understanding the image data**.

The next step was to use this knowledge to build a Machine Learning model capable of **classifying the handwritten digits**, which led to Task 03.

---

## Notebook

`digits_dataset_exploration.ipynb`

---

## Summary

**Task 02 introduced image-based Machine Learning data by exploring the Digits dataset, understanding pixel representations, performing image manipulation, analyzing pixel distributions, and visualizing average digit patterns.**


# Task 03 — MLP Digits Classifier

## Overview

This task focused on building a **Multi-Layer Perceptron (MLP) classifier** for handwritten digit recognition using the Scikit-learn Digits dataset.

The task moved from data exploration into actual Machine Learning model development. The MLP model was trained and evaluated, compared with a Logistic Regression baseline, and tested with different hidden-layer architectures to understand how neural-network structure affects performance.

---

## Task Objective

The main objectives were to:

* Build a neural-network-based classifier.
* Use `MLPClassifier` from Scikit-learn.
* Train the model on handwritten digit data.
* Evaluate training and testing performance.
* Compare MLP with Logistic Regression.
* Experiment with different hidden-layer configurations.
* Analyze potential overfitting.
* Observe the training loss and learning behavior.

The notebook explicitly focuses on comparing model performance and studying the effect of different hidden-layer configurations.

---

## Dataset

The **Scikit-learn Digits dataset** was used.

It contains handwritten digits from **0 to 9**, represented as 8 × 8 pixel images.

The image data was used as input features for the classification model.

---

## Work Completed

### 1. Data Preparation

The Digits dataset was loaded and prepared for Machine Learning.

The data was divided into training and testing subsets using `train_test_split`.

This allowed the model to learn from the training data and then be evaluated on previously unseen test data.

---

### 2. MLP Classifier

The main model used was:

```python
MLPClassifier
```

An initial MLP architecture with one hidden layer containing **32 neurons** was trained.

The model was configured with:

```text
Hidden layer: 32 neurons
Maximum iterations: 1000
Random state: 42
```

The model was trained using the training data and then used to generate predictions for both training and testing sets.

---

## Model Evaluation

The model was evaluated using **accuracy**.

The recorded result for the `(32,)` hidden-layer configuration was:

| Metric            |  Result |
| ----------------- | ------: |
| Training Accuracy | 100.00% |
| Testing Accuracy  |  97.78% |

The model therefore performed very well on both training and unseen testing data.

---

## Comparison with Logistic Regression

Logistic Regression was trained as a baseline model.

The recorded results were:

| Model               | Training Accuracy | Testing Accuracy |
| ------------------- | ----------------: | ---------------: |
| Logistic Regression |           100.00% |           97.50% |
| MLP                 |           100.00% |       **97.78%** |

The MLP achieved a slightly higher testing accuracy than the Logistic Regression baseline.

---

## Hidden-Layer Experiment

Different MLP architectures were tested to understand the effect of hidden-layer size and depth.

The configurations included:

```text
(8,)
(32,)
(128,)
(64, 32)
```

The recorded results were:

| Hidden Layer | Training Accuracy | Testing Accuracy |
| ------------ | ----------------: | ---------------: |
| (8,)         |           100.00% |           94.44% |
| (32,)        |           100.00% |       **97.78%** |
| (128,)       |           100.00% |       **97.78%** |
| (64, 32)     |           100.00% |           96.67% |

All configurations achieved 100% training accuracy, while testing accuracy varied. This demonstrated that increasing network size does not automatically guarantee better generalization.

---

## Overfitting Analysis

Because all tested architectures achieved perfect training accuracy while their testing accuracies were lower, the experiment provided an opportunity to observe the **generalization gap**.

For example:

```text
Training Accuracy = 100%
Testing Accuracy  = 97.78%
```

The difference indicates that the model performs slightly better on the data it was trained on than on unseen data.

However, the testing accuracy remains high, so the observed gap is relatively small.

---

## Learning Behavior

The notebook also examined the training loss and learning behavior of the MLP model.

This helped understand how the model learns during training and how the loss changes across iterations.

---

## Approach

The overall workflow was:

```text
Load Digits Dataset
        ↓
Split into Training & Testing Data
        ↓
Train Logistic Regression Baseline
        ↓
Train MLP Classifier
        ↓
Generate Predictions
        ↓
Calculate Accuracy
        ↓
Compare Models
        ↓
Test Multiple Hidden-Layer Architectures
        ↓
Analyze Generalization & Learning Behavior
```

---

## Technologies Used

* **Python**
* **Jupyter Notebook**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**
* `MLPClassifier`
* `LogisticRegression`
* `accuracy_score`
* `train_test_split`

---

## Key Concepts Learned

### Multi-Layer Perceptron

An MLP is a feed-forward artificial neural network containing one or more hidden layers.

### Hidden Layers

Hidden layers allow the network to learn intermediate representations from the input data.

### Training vs Testing Accuracy

Training accuracy measures performance on the data used for learning, while testing accuracy measures performance on unseen data.

### Generalization

A good model should not simply memorize training data. It should also perform well on unseen examples.

### Model Architecture

Changing the number of neurons and hidden layers can affect model performance and generalization.

---

## Learning Outcomes

This task helped me understand:

* How to build a neural-network classifier.
* How MLPs process classification data.
* How to train and evaluate a neural network.
* How to establish a baseline using Logistic Regression.
* How hidden-layer architecture affects model performance.
* How to compare training and testing performance.
* How to identify a training/testing performance gap.
* How to interpret learning curves and model behavior.

---

## Connection to Previous Task

Task 02 focused on understanding handwritten digit images and their numerical representation.

Task 03 built on that knowledge by using the same type of data to train an actual **neural-network classifier**.

---

## Notebook

`Day03_MLP_Digits_Classifier.ipynb`

---

## Summary

**Task 03 introduced practical neural-network classification using MLPClassifier, including model training, baseline comparison, architecture experiments, accuracy evaluation, and analysis of generalization.**


# Task 04 — MNIST MLP Classifier

## Overview

This task focused on handwritten digit classification using the **MNIST dataset** and a **Multi-Layer Perceptron (MLP)** classifier.

The task extended the concepts learned in the previous Digits classification exercise to a much larger and more realistic handwritten-digit dataset.

A major focus of this task was understanding the importance of **feature scaling** for neural-network training and evaluating the model using accuracy, a confusion matrix, and incorrect predictions.

---

## Task Objective

The main objectives were to:

* Work with the MNIST handwritten-digit dataset.
* Understand a larger image dataset.
* Explore grayscale image representation.
* Prepare pixel data for Machine Learning.
* Compare MLP performance with and without feature scaling.
* Train an MLP classifier.
* Measure testing accuracy.
* Analyze classification results using a confusion matrix.
* Identify incorrect predictions.

The notebook uses MNIST images of size **28 × 28 pixels** and evaluates the effect of scaling pixel values from 0–255 to 0–1.

---

## Dataset

The **MNIST dataset** contains handwritten digits from **0 to 9**.

The dataset used in the notebook contains:

* **70,000 images**
* **10 digit classes**
* Grayscale images
* Image resolution: **28 × 28 pixels**
* Pixel intensity range: **0–255**

Each image therefore contains:

```text
28 × 28 = 784 pixels
```

which can be represented as numerical input features for the MLP classifier.

---

## Work Completed

### 1. Dataset Loading

The MNIST dataset was loaded from **OpenML** and explored to understand its structure and image representation.

---

### 2. Image Visualization

Sample handwritten digit images were visualized to understand the dataset before training the model.

This connected the numerical pixel representation with the actual appearance of the handwritten digits.

---

### 3. Pixel Representation

The notebook examined how grayscale images are represented using numerical pixel values.

Each pixel contains an intensity value between:

```text
0 → Black
255 → White
```

---

## Feature Scaling

One of the main experiments in this task was comparing model performance before and after scaling the pixel values.

The original pixel values ranged from:

```text
0 – 255
```

They were scaled to:

```text
0 – 1
```

This was done to provide more suitable numerical input for the neural network.

---

## MLP Architecture

The MLP model used a hidden layer containing:

```text
32 neurons
```

The notebook trained the model under two conditions:

1. **Without feature scaling**
2. **With feature scaling**

This allowed the effect of scaling on model performance to be compared directly.

---

## Experiment 1 — Without Scaling

The MLP was trained using the original pixel values.

Recorded result:

| Metric           |            Result |
| ---------------- | ----------------: |
| Testing Accuracy |        **92.52%** |
| Training Time    | **10.95 seconds** |
| Convergence      |           Warning |

---

## Experiment 2 — With Scaling

The same MLP architecture was trained after scaling the pixel values from 0–255 to 0–1.

Recorded result:

| Metric           |            Result |
| ---------------- | ----------------: |
| Testing Accuracy |        **96.23%** |
| Training Time    | **11.49 seconds** |
| Convergence      |           Warning |

The scaled version improved testing accuracy from **92.52% to 96.23%**, while training time remained almost the same.

---

## Effect of Feature Scaling

The experiment demonstrated an important Machine Learning concept:

> **Feature scaling can significantly improve neural-network performance.**

In this experiment:

```text
Without Scaling → 92.52%
With Scaling    → 96.23%
```

This represents an improvement of approximately **3.71 percentage points** in testing accuracy.

The notebook also recorded convergence warnings because the configured maximum number of iterations was reached before the optimizer fully converged.

---

## Confusion Matrix

A confusion matrix was used to evaluate the classification results.

It provides a class-by-class view of the model's predictions.

The matrix helps identify:

* Correctly classified digits.
* Digits that were confused with other digits.
* Classes where the model performs strongly.
* Classes where the model makes more mistakes.

The diagonal entries represent correct predictions, while off-diagonal entries represent misclassifications.

---

## Incorrect Predictions

The notebook also visualized incorrectly classified images.

This helped investigate examples where the model predicted one digit while the actual label belonged to another class.

Studying these errors provides insight into the limitations of the classifier and the difficulty of distinguishing visually similar handwritten digits.

---

## Approach

The overall workflow was:

```text
Load MNIST Dataset
        ↓
Explore Dataset
        ↓
Visualize Sample Images
        ↓
Understand Pixel Values
        ↓
Prepare Train/Test Data
        ↓
Train MLP Without Scaling
        ↓
Evaluate Accuracy & Training Time
        ↓
Scale Pixel Values
        ↓
Train MLP With Scaling
        ↓
Compare Results
        ↓
Generate Confusion Matrix
        ↓
Analyze Incorrect Predictions
```

---

## Technologies Used

* **Python**
* **Jupyter Notebook**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**
* `MLPClassifier`
* `train_test_split`
* `accuracy_score`
* Confusion Matrix

---

## Key Concepts Learned

### MNIST Dataset

I learned how a large-scale handwritten-image dataset can be prepared and used for Machine Learning classification.

### Feature Scaling

Scaling numerical features can help neural-network optimization and improve model performance.

### MLP Classification

An MLP can learn patterns from pixel-level input features and classify handwritten digits.

### Confusion Matrix

A confusion matrix provides more detailed information about classification errors than accuracy alone.

### Error Analysis

Examining incorrectly classified images helps understand where and why a model makes mistakes.

### Convergence

The convergence warning demonstrated that the optimizer may require additional iterations or different training settings to fully converge.

---

## Learning Outcomes

After completing this task, I learned:

* How to work with a larger image dataset.
* How to prepare pixel-based features for an MLP.
* Why feature scaling matters for neural networks.
* How to compare model experiments fairly.
* How to evaluate classification performance.
* How to interpret a confusion matrix.
* How to investigate incorrect predictions.
* How training configuration affects convergence.

---
Task 04 therefore extended the previous MLP classification work to a larger dataset while introducing **feature scaling, confusion-matrix analysis, and error analysis**.

---

## Notebook

`Day04_MNIST_MLP_Classifier.ipynb`

---

## Summary

**Task 04 applied MLP classification to the MNIST dataset and demonstrated how feature scaling improved testing accuracy from 92.52% to 96.23%. The task also introduced confusion-matrix analysis and examination of incorrect predictions to better understand model performance.**



 

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


## Connection to Previous Tasks

The progression of the internship tasks was:

```text
Task 01
Iris Dataset Exploration
        ↓
Task 02
Digits Dataset & Image Exploration
        ↓
Task 03
MLP Classification on Digits
        ↓
Task 04
MLP Classification on MNIST
        ↓
Task 05
Simple Neural Network
        ↓
Task 06
Manual Neural Network Forward Pass
```



##  Author

**Sabreena Rashid**

GitHub: https://github.com/sabreena01
