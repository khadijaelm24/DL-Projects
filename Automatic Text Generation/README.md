
# Text Generation with LSTM Project

## Overview
This project implements a text generation model using a Long Short-Term Memory (LSTM) neural network. Inspired by *The Unreasonable Effectiveness of Recurrent Neural Networks*, this experiment utilizes the **TensorFlow** and **Keras** libraries to train a model on a dataset of Shakespeare's works, generating Shakespeare-like text. The goal is to explore the capabilities of RNNs in natural language generation.

## Features
- **Text Generation Model**: Trains a character-level LSTM model to generate text that resembles Shakespearean language.
- **Experiment with Hyperparameters**: Tests different model configurations, including the number of LSTM layers and neurons.
- **Real-time Text Sampling**: Generates text samples during training to monitor progress and observe the model's ability to produce coherent text.

## Technologies Used
- **TensorFlow**: Provides the deep learning framework used to build and train the LSTM model.
- **Keras API**: Offers high-level neural network APIs within TensorFlow to simplify model building.
- **NumPy**: Used for numerical operations and data manipulation.

## Setup
- Python 3.6 or above
- TensorFlow (version 2.x)

## How It Works
1. **Data Preparation**: Loads the Shakespeare dataset and preprocesses it into sequences of characters for training the model.
2. **Model Architecture**: Builds an LSTM model capable of learning the character-level patterns in the text.
3. **Training and Evaluation**: Trains the model on the preprocessed text data, periodically sampling text to monitor the generation quality.
4. **Text Generation**: Once trained, the model generates new text by predicting one character at a time based on previous ones, simulating Shakespearean writing.
