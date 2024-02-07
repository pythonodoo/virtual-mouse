# Virtual-Mouse Hand base 
# Hand Gesture Based Virtual Mouse: An Interactive Teacher Assistant

# Introduction
The mouse is one of the wonderful inventions of Human-Computer Interaction
(HCI) technology. Currently, wireless mouse or a Bluetooth mouse still uses devices and
is not free of devices completely since it uses a battery for power and a dongle to connect
it to the PC. In the proposed Hand Gesture Based Virtual Mouse: An Interactive
Teaching Assistant, this limitation can be overcome by employing webcam or a built-in
camera for capturing of hand gestures and hand tip detection using computer vision. The
algorithm used in the system makes use of the machine learning algorithm. Based on the
hand gestures, the computer can be controlled virtually and can perform left click, right
click, scrolling functions, and computer cursor function without the use of the physical
mouse. The algorithm is based on deep learning for detecting the hands. Hence, the
proposed system will provide an interactive way of Human-Machine Interaction and also
avoid COVID-19 and other fatal diseases spread by eliminating the human intervention
and dependency of devices to control the computer.

# Requirements Libraries
Install tk for mouse info in step one
1: sudo apt-get install python3-tk python3-dev 

import the file that will track hand
2: HandTrackingModule

Also install the following libraries
3: mediapipe
4: opencv-python 
5: pyautogui 
6: numpy 
7: time 
8: math 

# Funcationalities

# 1: For the Mouse Cursor Moving around the Computer Window
If the index finger is up with tip Id = 1 or both the index finger with tip Id = 1 and
the thumb with tip Id = 0 are up, the mouse cursor is made to move around the window of
the computer using the PyautoGui package of Python.

# 2: For the Mouse to Perform Left Button Click
If both the index finger with tip Id = 1 and the middle finger with tip Id = 2 are up
and the distance between the two fingers is greater than 100px, the computer is made to
perform the left mouse button click using the puautogui Python package.

# 3: For the Mouse to Perform Right Button Click
If both the index finger with tip Id = 1 and the middle finger with tip Id = 2 are up
and the distance between the two fingers is lesser than 40 px, the computer is made to
perform the right mouse button click using the pyautogui Python package.

# 4: For the Mouse to Perform Scroll down Function
If only the little finger with tip Id = 1 is up, the computer is made to perform the
scroll mouse function using the PyAutoGUI Python package.

# 5: For the Mouse to Perform Scroll Up Function
If all the fingers are up with tip Id = 0, 1, 2, 3, and 4, the computer is made to not
perform any mouse events in the screen.

# 6: For No Action to be Performed on the Screen
If all the fingers are up with tip Id = 0, 1, 2, 3, and 4, the computer is made to not
perform any mouse events in the screen.

# 7: For Volume Up
If the little finger with tip id = 4 and thumb finger with tip id = 0 are up and the
remaining fingers are down, the computer is made to perform the Volume Up Function
using the PyAutoGUI Python package.

# 8: Volume Down Gesture
If the fingers with tip ids = 2, 3, 4 are up while index and thumb fingers are down,
the computer is used to perform the Volume down function using PyAutoGUI Python
package.
