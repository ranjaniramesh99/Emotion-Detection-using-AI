# Emotion-Detection-using-AI
This is an emotion detection project which serves to classify images depicting human emotions into 5 basic emotions - happiness, sadness, anger, neutral and surprise. 

Detailed Description:
This project contains 6 different ML models for this image classification problem:
1. KNN - K Nearest Neighbors
2. Lgistic Regression
3. Desicion Tree 
4. SNN - Standard Neural Network 
5. CNN - Convolutional Neural Networks
6. VGG 16 - Transfer Learning Model
The highest accuracy was achieved by the VGG Model which presented an accuracy of 68.05%

A CSV file which contained images as strings was used for the training and testing. The higher ML models (SNN onwards) ran 20 epochs of training each. 
To identify the best features to use for the models to yield best results, both facial landmarks to detect facial features (using dlib frontal face detector) and Euclidean distances which measured the distances between various facial features. The application Euclidean distances can be seen through an example - When person is angry, he or she may enlarge his/ her eyes and may even furrow his/her eyebrows. Thus, the Euclidean distance between the end points of the eyelids may increase and the distance between the top eyelid and the eyebrow may decrease. These Euclidean distances were used as a basis for classification of the images. 


