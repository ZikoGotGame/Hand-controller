# Hand-controller
The program is originally a sample to showcase how openCV and mediapipe can work in conjunction with each other to allow for hand gesture recognition. This version utilizes PyAutoGUI to control the mouse using hand position with an open hand. A closed hand left clicks the mouse. Custom hand gestures can be added by adding values to the keypoint.csv file and then launching keypoint_classification.ipynb in Jupyter Notebook. Be sure to increase the number of classes in Jupyter Notebook before running to add a new gesture. This is the link to the original work: https://github.com/kinivi/hand-gesture-recognition-mediapipe

This program adds extra functionality to the original work.

The added functionality includes:

- Ability to control computer mouse from webcam.
