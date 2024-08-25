# Covid Image Classification

## Overview

This project is a deep learning application for classifying chest X-ray images into three categories: Covid-19, Viral Pneumonia and Normal.
The classification model using deep learning techniques to differentiate between three classes based on the provided dataset.

## Dataset

The dataset used on this project is available on [Kaggle](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset)
The dataset consist of three classes:
- **Covid-19**: X-ray images of patients with covid-19.
- **Viral Pneumonia**: X-ray images of patients with viral pneumonia.
- **Normal**: X-ray images of healthy patients.

## Model Architecture

This project make use of Alexnet, the convolutional neural network model already proven effective in image classification tasks.
The network consist of convolutional layers followed by fully connected layers.

## Training

The model trained on kaggle cpu.

### HyperParams

- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy (Multi Classification)
- **Batch Size**: 32
- **Learning Rate**: 0.001

## Evaluation

The above hyper parameter have used for training and the model was evaluated on testing data, acheiving an accuracy of **83%**.



