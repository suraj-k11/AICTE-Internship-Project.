Week 3: Smart Garbage Classifier Using CNN
1. Project Overview

This project implements a Convolutional Neural Network (CNN) to classify different types of garbage (plastic, paper, metal, etc.) from images. The model is trained on a publicly available dataset and predicts the category of garbage with high accuracy.

2. Dataset

Dataset Name: Garbage Classification Dataset

Source: Kaggle (Uploader: namanjain001)

Classes: Plastic, Paper, Metal, Cardboard, Trash, etc.

Preprocessing: Images resized, normalized, and split into train/validation sets using ImageDataGenerator.

3. Model Architecture

Input: Images of size (64,64,3)

CNN Layers: Multiple Conv2D + MaxPooling layers

Activation: ReLU

Output Layer: Softmax activation for multi-class classification

Optimizer: Adam

Loss Function: Categorical Crossentropy

The model was trained for 10 epochs with validation.

4. How to Run

Clone this repo.

Ensure all dependencies in requirements.txt are installed.

Open the notebook Week3_Smart_Garbage_Classifier.ipynb.

Run all cells sequentially to reproduce training, evaluation, and plots.
