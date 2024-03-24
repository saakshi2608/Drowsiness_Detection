# Drowsiness_Detection
This code can detect the eyes and alert when the user is drowsy.
This can be used by riders who tend to drive for a longer period of time that may lead to accidents.
Dependencies
1)import cv2
2)import imutils
3)import dlib
4)import scipy
Algorithm :
Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye.
It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.
