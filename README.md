# Emotion-Detection-using-AI
This is an emotion detection project which serves to classify images depicting human emotions into 5 basic emotions - happiness, sadness, anger, neutral and surprise. I used Google Colaboratory for this project as it makes imposting packages and sectioning the code into smaller pieces, easy. 

Detailed Description:
This project explores 6 different ML models for this image classification problem:
1. KNN - K Nearest Neighbors
2. Lgistic Regression
3. Descision Tree 
4. SNN - Standard Neural Network 
5. CNN - Convolutional Neural Networks
6. VGG 16 - Transfer Learning Model

The first three models (upto desicion tree) ran on a CPU instance while the higher ML models ran on a GPU instance. 
The highest accuracy was achieved by the VGG Model, which presented an accuracy of 68.05%

A CSV file which contained images as strings was used for the training and testing process. The higher ML models (SNN onwards) ran 20 epochs of training each to achieve best training of the model. 

To identify the best features to use for the models to yield best results, both facial landmarks to detect facial features (using dlib frontal face detector), and Euclidean distances which measured the distances between various facial features were used. The application of Euclidean distances can be seen through an example - When a person is angry, he/she may enlarge his/ her eyes and may even furrow his/her eyebrows. Thus, the Euclidean distance between the end points of the eyelids may increase and the distance between the top eyelid and the eyebrow may decrease. These Euclidean distances were used as a basis for classification of the images. 

This project helped me understand the different applictaions of Machine Learning models in a real-world scenario and helped me learn a lot about the process of building, training and testing models. 
I started off this project at the Inspirit AI course. This course gave me an insight into the different kinds of models which can be used and also helped me understand the various applications of AI, such as AI in healthcare, AI in astronomy, AI in social media and much more. 
I further developed on my work at Inspirit AI for a school computer science project, which I lead. 
The code in this repository is the final result of my work!


