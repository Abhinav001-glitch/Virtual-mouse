## OVERVIEW
The Virtual Mouse project is an implementation of a human-computer interaction system that allows users to control the cursor on their computer screen without the need for a physical mouse. This project uses computer vision techniques to detect and interpret hand gestures as input commands.

## Requirements
The library required for this project are,
  1.  OpenCV    : For image and video processing
  2.  MediaPipe : For hand tracking and gesture recognition
  3.  PyAutoGUI : For controlling the mouse pointer

## Functioning
  ![image](https://github.com/user-attachments/assets/74ff1a84-4e17-4444-9e18-92a99217d8f7)

  In start we use cv2 to start video capturing. Then we use mediapipe to make landmark on hand which further will be used to collect data like sepration between index and thumb-finger and getting id of Index finger. Then we use Pyautogui to connect the cursor with index finger and do click function when the distance between the index finger and the thumb is very less. 


## Limitation
   1. The performace of the code will depend on the quality of the webcame used.
   2. It requires proper hand positioning inside the frame for accurate outcome.
   3. Only one hand can be used at a time in the frame, as using both in the frame at the same time may lead to failure.

## Acknowledgements 
   Mediapipe for the hand tracking library.
   OpenCV for robust image processing tools.
   PyAutoGUI for seamless desktop control.

   
