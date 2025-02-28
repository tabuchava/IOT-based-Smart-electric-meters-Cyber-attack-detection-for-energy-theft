# Electricity Theft Detection using Deep Learning  

This project implements an electricity theft detection system using IoT-based smart electric meters. It leverages Deep Learning models such as CNN, GRU, and Feed Forward Neural Networks (DNN) to identify fraudulent electricity consumption patterns.

### Table of Contents 

1. [Introduction](#electricity-theft-detection-using-deep-learning)  
2. [Features](#features)  
3. [Dataset](#dataset)   
4. [Installation & Setup](#installation--setup)  
   - [Install Dependencies](#1️⃣-install-dependencies)  
   - [Run the Application](#2️⃣-run-the-application)  
   - [Usage](#3️⃣-usage)  
6. [Model Architectures](#model-architectures)  
   - [Convolutional Neural Network (CNN)](#-convolutional-neural-network-cnn)  
   - [Gated Recurrent Unit (GRU)](#-gated-recurrent-unit-gru)  
   - [Feed Forward Neural Network (DNN)](#-feed-forward-neural-network-dnn)  
7. [Results & Performance](#results--performance)  
8. [Screenshots](#screenshots)  

## Features  
- Electricity theft detection using Deep Learning models  
- Multiple classification models: CNN, GRU, and DNN  
- Data preprocessing and visualization  
- Model evaluation using precision, recall, F1-score, and accuracy  
- Graphical User Interface (GUI) using Tkinter  

## *Dataset*  
The dataset used for training the models is available on Kaggle:  
[Fraud Detection in Electricity and Gas Consumption](https://www.kaggle.com/mrmorj/fraud-detection-in-electricity-and-gas-consumption?select=client_train.csv)  

## Installation & Setup  

### Install Dependencies 
Ensure Python 3.x is installed. Install the required libraries using:  
bash
pip install -r requirements.txt
  

### Run the Application  
Execute the Python script to launch the GUI:  
bash
python ElectricityTheftDetection.py
  

### Usage 
1. *Upload Dataset* → Load the electricity consumption dataset.  
2. *Preprocess Dataset* → Clean and encode the dataset.  
3. *Train Models* → Choose from DNN, CNN, or GRU to train the model.  
4. *Predict Theft* → Test the trained model on new data.  
5. *View Performance* → Compare model accuracy, precision, recall, and F1-score.

## Model Architectures  

### Convolutional Neural Network (CNN) 
- 2 Convolutional layers with ReLU activation  
- MaxPooling layers  
- Fully connected Dense layers  
- Softmax output for classification  

### Gated Recurrent Unit (GRU) 
- Bidirectional GRU layers  
- Dropout layers for regularization  
- Dense Softmax layer for classification  

### Feed Forward Neural Network (DNN)
- Fully connected layers with ReLU activation  
- Output layer with Softmax activation for binary classification  

## Results & Performance 
The models are evaluated using:  
Accuracy – Measures overall prediction correctness  
Precision – How many detected theft cases are correct  
Recall – How many actual theft cases were detected  
F1-score – Harmonic mean of precision and recall  

## Screenshots 
GUI Interface for Electricity Theft Detection:  
[GUI Screenshot](https://via.placeholder.com/800x400.png?text=GUI+Screenshot)  

Performance Comparison Graph:  
[Performance Graph](https://via.placeholder.com/800x400.png?text=Performance+Graph)  

