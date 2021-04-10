# Pneumonia-Detection-Using-Chest-X-ray-Scans By Team Endurance

## *Abstract*

The risk of pneumonia is immense for many, especially in developing nations where billions face energy poverty and rely on polluting forms of energy. The WHO estimates that over 4 million premature deaths occur annually from household air pollution-related diseases including pneumonia. Over 150 million people get infected with pneumonia on an annual basis especially children under 5 years old.

## *Objectives:*

### The HealthCare Challenge?
Build an algorithm using AI/ML models to automatically identify whether a patient is suffering from pneumonia or not by looking at chest X-ray images. 

<img src="https://miro.medium.com/max/3000/1*J5wUMztRXZ_eHimMxULAnA.png">


We aim at creating a model for scanning **Chest x-ray images** and classifying as Pneumoniatic / Normal x-rays. The model has been developed using **TensorFlow and Keras** using Transfer Learning using **VGG19**. 

### *Concepts:*
1. Convolutional Neural Networks
2. Transfer Learning
3. Early stopping (to avoid overfitting) 
4. Callbacks

### *Environment & Tools:*
1. TensorFlow
2. Keras
3. Pandas
4. Numpy
5. Matplotlib
6. Kaggle API
7. Flask

### *Pretrained Model used:*
#### VGG19 trained on ImageNet dataset

### *Dataset used:*
Kaggle dataset: [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)


**Code : Provided in the same repository**


### *Conclusions:*
We have demonstrated how to classify positive and negative pneumonia data from a collection of X-ray images. The model was made from scratch, which separates it from other methods that rely heavily on transfer learning approach. In the future this work could be extended to detect and classify X-ray images consisting of lung cancer or even the disease causing widespread pandemic COVID-19
