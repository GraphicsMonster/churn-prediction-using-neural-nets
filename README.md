# Churn Prediction Model

## Overview

This repository contains a churn prediction model implemented in Python using PyTorch. The model is trained to predict customer churn based on features such as credit score, age, tenure, balance, and more. The project was developed for the Kaggle Playground Series Season 4 Episode 1 competition.

## Key Features

- PyTorch implementation of a feedforward neural network.
- Trained on Kaggle competition dataset.
- Achieved 86.9% accuracy on the validation set.

## Usage

### Pre-trained Model

The pre-trained model weights are available in the `Weights/` folder. You can use these weights to make predictions on new data. 

### Train your own model

If you want to train your own model, run the model.ipynb notebook with any required adjustments in the hyperparams. Save the model parameters and run inferences on your own test set.

## Model Architecture

The model architecture consists of a feedforward neural network with configurable hidden layers and sizes. Each hidden layer employs a ReLU activation function, and the output layer is configured with a sigmoid activation to generate predictions. Specifically:

- **Hidden Layers:** 3 layers
- **Neurons per Hidden Layer:** 64
- **Learning Rate:** 1e-4

This configuration yielded the best performance on the validation set, achieving an accuracy of 86.9%.

## Results

- **Validation accuracy** -- 86.9%
- **Test set submission score** -- 0.87600

## Acknowledgements

- Developed for the Kaggle Playground Series Season 4 Episode 1 competition.
- Kaggle competition link: [Playground Series - Season 4, Episode 1.](https://www.kaggle.com/competitions/playground-series-s4e1/overview)

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).