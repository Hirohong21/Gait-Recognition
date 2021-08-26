# Gait-Recognition
## Abstract. 
Gait recognition is a new type of biometric recognition technology, which aims to identify people's walking posture. In this project, we propose a new method for gait recognition. We use MediaPipe Holistic Framework to identify the Key Points of human body features, construct a human posture feature map, and then use these Key Points of human body features to perform gait recognition. The proposed scheme contains three stages: 
- Obtain Key Point data of 20 human body characteristics from the CASIA Gait Recognition Dataset. 
- Use the machine learning algorithm model to train the obtained Key data of the human body characteristics of 20 people. 
- Input the data of the Key Points of the human body characteristics of the new test subject through the camera and train the model again.
- finally test the new subject to determine the accuracy of the method and the performance of the real-time test. 

The results show that the method's accuracy has reached more than 90%, so it can be considered that the proposed scheme is effective.

## Enviroment
MediaPipe == 0.8.5

## Install MediaPipe
pip install MediaPipe ==0.8.5

## Dataset
All datasets are from the  CASIA Gait Recognition Dataset

## Matters needing attention
Due to the size of the file, the datasets and the models of the project are in "releases", please pay attention to the file reading path when using them
