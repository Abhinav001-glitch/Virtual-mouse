## OVERVIEW
The Virtual Mouse project is an implementation of a human-computer interaction system that allows users to control the cursor on their computer screen without the need for a physical mouse. This project uses computer vision techniques to detect and interpret hand gestures as input commands.

## Requirements
The library required for this project are,
  1.  OpenCV    : For image and video processing
  2.  MediaPipe : For hand tracking and gesture recognition
  3.  PyAutoGUI : For controlling the mouse pointer

## Limitation
   1. The performace of the code will depend on the quality of the webcame used.
   2. It requires proper hand positioning inside the frame for accurate outcome.
   3. Only one hand can be used at a time in the frame, as using both in the frame at the same time may lead to failure.

## Acknowledgements 
   Mediapipe for the hand tracking library.
   OpenCV for robust image processing tools.
   PyAutoGUI for seamless desktop control.

   
