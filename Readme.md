# Gesture volume control
In this project I am going to learn how to use Gesture Control to change the volume of a computer. 
I first look into hand tracking and then I will use the hand landmarks to find gesture of my hand to change the volume.

## Features
* Can track your hand in real-time
* Can change your computer's volume based on your hand activity

## How to install
1. Clone this repository on your computer
`https://github.com/paveldat/gesture_volume_control.git`
2. Install all the requirements
`run libraries.bat`
3. Run the program
`python main.py`

## Help
You might face issue with webcam not showing and you get errors.
To solve it just change the value in this line (for example to `1`).
`cap = cv2.VideoCapture(0)`
Increment this number until you see your webcam.

## Hand Landmarks
<img src="https://github.com/paveldat/gesture_volume_control/blob/main/img/HandLandmarks.png">

## Result
![Alt Text](https://github.com/paveldat/gesture_volume_control/blob/main/img/1.gif)