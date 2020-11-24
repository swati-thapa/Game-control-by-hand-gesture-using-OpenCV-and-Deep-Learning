# Game-control-by-hand-gesture-using-OpenCV-and-Deep-Learning

In this project, I have tried to control the game movement using hand gestures. Here I have used pydirectinput where I have tried control keyboard keys which in turn control the game movement. I have used different types of gestures namely fist, HiFi,V, and thumbs up out of which I have used thumbs up for upward movement.

Steps to follow:
1. First run gather.py file to gather data of your own. Data collected are data with thresholding technique which helps us to differentiate hand from the background.
2. I have used this data and have implemented a neural network where simple CNN was used for training. I had tried it with different transfer learning techniques but after fixing overfitting(using l2 regularizer) I got the best accuracy.
3. Later I integrated these hand gestures with some selected keyboard keys using pydirectinput.
4. As a result I was able to control the up arrow key in the keyboard resulting in an upward movement in the game.

![ezgif-5-4d64ad621c3a](https://user-images.githubusercontent.com/61458877/97389430-4435c100-1900-11eb-83e8-9fcdc26041ca.gif)

