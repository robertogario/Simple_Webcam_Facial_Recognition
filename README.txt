# Simple Webcam Facial Recognition

This uses the facial_recognition python library, along with cv2, the Open Computer Vision library.

The data folder contains images of different people, which then need to be written into the code.

These images are processed when loading the program, to memorise faces, and then anyone who appears in front of the webcam will be matched against them.

The program stores whether or not someone is a friend, then highlights friends in green and foes (or unknown) in red.