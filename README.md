# Bilinear EfficientNet with Focal Loss + Label Smoothing  

## Plant Pathology  
![python](/images/header.png)  

### Problem Objectives:
The aim of this challenge is to build a Generalised Model for the task of Image Classification. We have to also deal with Class Imbalance Problem and detect Fine Grained details which differentiates whether the leaf is diseased or Not.

### Solution:  
i) Image Classification: **EfficientNet**  

ii) Class Imbalance and Generalization : **Focal Loss + Label Smoothing**  

iii) Detect Fine Grain Details: **Bilinear CNN**  


### Model: BiLinear EfficientNet with Focal Loss+ Label Smoothing
![python](/images/BiLinearModel.PNG)  

### Expriments and Results:
a) Selecting the Best and Efficient CNN Backbone (img size:380x380):  
![python](/images/models1.png)  
b) Exprimenting with Loss Functions (img size:380x380):  
![python](/images/lossCompare.PNG)  
c) Bilinear CNN (img size:760x760):  
![python](/images/LS_1.PNG)  
![python](/images/loss.png)  

### References:
(1) EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks 
    (http://https//arxiv.org/abs/1905.11946)  
(2) Focal Loss for Dense Object Detection
    (https://arxiv.org/abs/1708.02002)  
(3) Bilinear CNNs for Fine-grained Visual Recognition
    (https://arxiv.org/abs/1504.07889)  
(4) Focal Loss Implementation
    (https://github.com/aldi-dimara/keras-focal-loss)  
(5) Label Smoothing Explaination and Formulas
    (https://towardsdatascience.com/what-is-label-smoothing-108debd7ef06)  
(6) BiLinear CNN Implementation
    (https://medium.com/@scorrea92/bilinear-cnn-models-in-tensorflow-keras-801121cc8c4d)  

Notebook: https://www.kaggle.com/jimitshah777/bilinear-efficientnet-focal-loss-label-smoothing  
Checkout my rank in this Kaggle Competition here: https://www.kaggle.com/jimitshah777


