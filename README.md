
# REAL-TIME GENDER CLASSIFICATION

![Python](https://img.shields.io/badge/Python-3.8-blueviolet) 


## Overview
Gender classification play an important role in many scenarios. It was first perceived as an issue
in psychophysical studies, it focuses on the efforts of understanding human visual processing and 
identifying key features used to categorize between male and female individuals. There are many methods
for classifying using machine learning such as KNN, or Multilayer Perceptron(MLP) and so on. 
However, in a real-world environment, the challenge is how to deal with the facial image being affected by the variance in factors such as illumination, pose, facial expression, occlusion, background information, and noise.
This is then also the challenge in the development of a robust face-basedgender classification system that has high classification accuracy and real-time performance.
The convolutional neural network(CNN) can solve the aforementioned problem. The main advantage of CNN compared to its predecessors is that it automatically detects the important features without any human supervision.
## DEMO
FOR REAL TIME FEMALE CLASSIFICATION
![Recommendation App](https://github.com/HungVoCs47/Gender-Classification/blob/main/image/Screenshot%20(1427).png)


FOR REAL TIME MALE CLASSIFICATION
![Recommendation App](https://github.com/HungVoCs47/Gender-Classification/blob/main/image/Screenshot%20(1444).png)


## DETECTION METHOD
This section introduces methods which were used in our experiments. The ﬁrstsubsection presents our recommended method in details.
ALEXnet Style:
![Recommendation App](https://github.com/HungVoCs47/Gender-Classification/blob/main/image/Screenshot%202022-10-15%20204312.png)
LeNet Style:
![Recommendation App](https://github.com/HungVoCs47/Gender-Classification/blob/main/image/Screenshot%202022-10-15%20205107.png)
## MODEL EVALUATION
![Recommendation App](https://github.com/HungVoCs47/Gender-Classification/blob/main/image/t%E1%BA%A3i%20xu%E1%BB%91ng%20(2).png)\
The loss function converge after 20 epochs. The validation accuracy of the last epochs is 97.6%, which is relatively high. The train and validation accuracy in the training stage increase after each one epoch. The ﬁgures show that the convolutional neural networks have outperformed in gender detection in real-world environments.\
![Recommendation App](https://github.com/HungVoCs47/Gender-Classification/blob/main/image/t%E1%BA%A3i%20xu%E1%BB%91ng%20(3).png)\
The above figure respresent the ROC curve of the model, the AUC measures the entire two-dimensional area underneath the entire ROC curve which is high, about 0.9961. The AUC provides an aggregate measure of performance across all possible classification threshold, and the highest AUC is 1(False positive rate = 0 and True positive rate = 1) and we can conclude that this model is good.\
|Threshold                                                            |F1-score    |Accuracy|
|--------------------------------------------------------------------------------------|--------------|----------------|
|P = 0.4 |F1 = 0.963 |Acc = 0.970          |
|P = 0.5       |F1 =  0.961         |Acc =    0.969     |






