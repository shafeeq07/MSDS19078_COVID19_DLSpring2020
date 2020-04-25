# MSDS19078_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.
# Dataset
Dataset used for this assignment can be found [here](https://drive.google.com/open?id=1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK).

https://drive.google.com/open?id=1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK

# Task 1 - A: Fine Tune only FC Layers of VGG16
In this task FC layers are replaced with 2 custom layers and all feature layers are freezed then trained model on given dataset.
```
Train Accuracy: 0.9414 | F1 Score: 0.9508
Validation Accuracy: 0.8980 | F1 Score: 0.9133
Test Accuracy: 0.9553 | F1 Score: 0.9626
```
<img src='results/cm_vgg16_fc_only.png'>
<img src='results/curves_vgg16_fc_only.png'>


# Task 1 - B: Fine Tune only FC Layers of ResNet18
In this task FC layers are replaced with 2 custom layers and all feature layers are freezed then trained model on given dataset.
```
Train Accuracy: 0.9028 | F1 Score: 0.9204
Validation Accuracy: 0.8767 | F1 Score: 0.8976
Test Accuracy: 0.9360 | F1 Score: 0.9470
```
<img src='results/cm_resnet18_fc_only.png'>
<img src='results/curves_resnet18_fc_only.png'>

# Task 2 - A: Fine Tune entire VGG16
In this task FC layers are replaced with 2 custom layers and all feature layers are unfreezed then trained model on given dataset.
```
Train Accuracy: 0.9751 | F1 Score: 0.9789
Validation Accuracy: 0.9260 | F1 Score: 0.9373
Test Accuracy: 0.9793 | F1 Score: 0.9825
```
<img src='results/cm_vgg16_entire.png'>
<img src='results/curves_vgg16_entire.png'>

# Task 2 - B: Fine Tune entire ResNet18
In this task FC layers are replaced with 2 custom layers and all feature layers are unfreezed then trained model on given dataset.
```
Train Accuracy: 0.9810 | F1 Score: 0.9840
Validation Accuracy: 0.9240 | F1 Score: 0.9360
Test Accuracy: 0.9713 | F1 Score: 0.9759
```
<img src='results/cm_resnet18_entire.png'>
<img src='results/curves_resnet18_entire.png'>

# Trained Models 
Weights of trained models can be found [here](https://drive.google.com/drive/folders/1wUg1gCygCSDe23Gnr8DKXVBpzHwPYACF?usp=sharing)

https://drive.google.com/drive/folders/1wUg1gCygCSDe23Gnr8DKXVBpzHwPYACF?usp=sharing