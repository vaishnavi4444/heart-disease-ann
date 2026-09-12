# Heart Disease Prediction using ANN

This project uses an Artificial Neural Network (ANN) to predict whether a person is likely to have heart disease based on different clinical features.

I built this project to get practical experience with neural networks and understand how the concepts I learned in machine learning can be applied to a real dataset.

## About the Project

The dataset contains information about patients such as age, sex, blood pressure, cholesterol, maximum heart rate, and other health-related features.

The model takes 13 features as input and predicts one of two outcomes:

- `0` – No heart disease
- `1` – Heart disease

## What I Did

The project follows a simple machine learning workflow:

1. Loaded and explored the dataset using Pandas.
2. Split the data into training and testing sets.
3. Standardized the input features using `StandardScaler`.
4. Built an Artificial Neural Network 
5. Trained the model using the Adam optimizer.
6. Evaluated the model using accuracy and a confusion matrix.
7. Tested the trained model with new input data.

## Model

The ANN consists of:

- Input layer – 13 features
- Hidden layer – 8 neurons with ReLU activation
- Hidden layer – 14 neurons with ReLU activation
- Output layer – 1 neuron with Sigmoid activation

Since this is a binary classification problem, I used binary cross-entropy as the loss function.

## Results

The model achieved approximately **83.5% accuracy** on the test dataset.

I also tested the trained model with a new input and obtained a prediction probability of approximately **0.91**, which resulted in a prediction of:

**Heart Disease: YES**
