# Flower Classification using Inception Model
## Overview

This repository focuses on building and training `Inception models` for flower classification using TensorFlow and Keras. Two approaches are explored: `building the Inception model from scratch` and utilizing **pre-trained** weights from Keras' `InceptionV3` model.

## Key Feature 
### 1. Dataset
------------------------------------------------------------------
The dataset used for training the models is the Flowers Recognition dataset, which includes images of flowers categorized as [0, 1, 2, 3, 4]. The dataset can be found here.

### 2. Models 
------------------------------------------------------------------
#### 1. Inception Model from Scratch
1. Architecture
    - Convolutional layers, pooling layers, inception modules, dropout layers, and fully connected layers.

2. Training
    - Compiled with Adam optimizer and sparse categorical crossentropy loss.
    - 100 epochs, batch size of 256.


#### 2. Inception Model with Pre-trained Weights

1. Architecture
    - Built using pre-trained weights from Keras' InceptionV3 model.
    - Fine-tuned on the flower dataset.

2. Training
    - Fine-tuned over 100 epochs, batch size of 256.



### 3. Learning Curve
------------------------------------------------------------------
- Plots for training and validation loss for both models.
- Plots for training and validation accuracy for both models.

### 4. Evaluation Metrics and Confusion Matrices
------------------------------------------------------------------
- Generate confusion matrices for testing samples on both custom and pre-trained models. 
- Calculate precision, recall, and F1 score to assess model performance.

### 5. Results Analysis
------------------------------------------------------------------
- Explores and comments on the results obtained from custom and pre-trained models.
- Analyzes the impact of transfer learning on classification accuracy and training efficiency.