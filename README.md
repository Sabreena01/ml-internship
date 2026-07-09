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

## Day 01 - Exploring the Iris Dataset

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


## Day 02 - Exploring the Digits Dataset

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


##  Day 03 - Neural Networks with the Digits Dataset

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

 **Notebook:** `day-03/Day03_MLP_Digits_Classifier.ipynb`
 
# Day 04 - MNIST Handwritten Digit Classification using MLP

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

## Files

- `Day04_MNIST_MLP_Classifier.ipynb`

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



##  Author

**Sabreena Rashid**

GitHub: https://github.com/sabreena01
