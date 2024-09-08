
# Augmented-ResNet-CNN for Traffic Sign Classification




## Overview


The Augmented-ResNet-CNN is a Convolutional Neural Network (CNN) model designed for predicting traffic signs. This model leverages data augmentation techniques to enhance performance and employs a ResNet-inspired architecture to achieve high accuracy in traffic sign classification tasks.

## Features
- Data Augmentation: Utilizes rotation, zoom, and shifts to increase the robustness of the model.
- ResNet-Inspired Architecture: Incorporates residual blocks for improved accuracy and learning efficiency.
- Model Evaluation: Provides metrics including precision, recall, and F1-score for various classes.
- Predictions and Visualization: Includes functionality for visualizing predictions and converting labels to speech.

## Dataset
The dataset used is the preprocessed traffic signs dataset available on Kaggle.

## Model Architecture
The CNN model includes the following architecture:

- Input Layer: 32x32x3
- Convolutional Layers: Multiple Conv2D layers with BatchNormalization and ReLU activations
- Pooling Layers: MaxPooling2D
- Global Pooling: GlobalAveragePooling2D
- Fully Connected Layer: Dense with softmax activation



## Performance

Accuracy Metrics
|Metric	|Value
| :-------- | :------- |
|Accuracy 	|0.9048         
|Macro Avg Precision 	|0.8977  
|Macro Avg Recall	    |0.8784  
|Macro Avg F1-Score	    |0.8822  
|Weighted Avg Precision |0.9104
|Weighted Avg Recall   	|0.9048
|Weighted Avg F1-Score 	|0.9044
|Total Support	        |12630  


## Contributing
Feel free to fork this repository and submit pull requests.