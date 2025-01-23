# Hand pose classification

In this project, we'll be doing hand pose classification based on the landmarks provided by [Mediapipe](https://google.github.io/mediapipe/solutions/hands#python-solution-api)
The idea is to classify the hand poses on the extracted landmarks (3D) rather than on the image itself.

I'd like to discuss 2 approaches to this problem. 
1. Using the landmarks from mediapipe to train a deep learning model to do the classification based on landmarks instead of the image itself.
2. Using the landmarks from mediapipe to classify the poses based on the landmarks. 


![](hand_landmarks.png)

Video demo can be found on [youtube](https://youtu.be/3V5tQBCl8wQ)


To know more about the project please refer to this ![blog](https://sher-somas.github.io/posts/2012/08/hand-gesture-classification/)

