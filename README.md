# Handwritten-Digits-Recognition

This project of Handwritten Digits Recognition aims to create and train a model using a Deep Learning Approach, especially using Computer Vision, based on CNN (Convolutional Neural Networks).

## Objective
The project aims to develop a model that can accurately recognize handwritten digits using the MNIST dataset.

## Data Used
The MNIST handwritten digits dataset, that is accessible through **TensorFlow** and **Keras**.

## Project Steps

### Data Preparation
- **Loading the Dataset:** The MNIST dataset is loaded using TensorFlow's Keras API.
- **Data Visualization:** We utilize **Matplotlib** to visualize the first image of the training dataset, helping to understand the nature of the data.
- **Pixel Value Inspection:** We check the pixel values before normalization to understand the original data distribution.
- **Normalization:** The pixel values are normalized to scale them, which improves training efficiency.
- **Image Resizing:** The images are resized to ensure they are suitable for applying the **Convolution Operation** effectively.

### Model Creation
- Creating a **Deep Neural Network** to train on the samples of the MNIST handwritten dataset, allowing for the recognition of handwritten digits.
