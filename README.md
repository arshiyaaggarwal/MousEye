# MousEye
Mouseye is an application which simulates mouse click events through eye blinks using OpenCV with the help of imutils and dlib libraries.

---------------------------------
#### To run:

Run facial_keypoints.py by adding the arguments as the path to the image and the path to the facial landmark predictor.

Run video_facial_landmarks.py by adding the arguments as the path to the facial landmark predictor and whether or not the Raspberry Pi camera should be used (by default the PC's webcam is used)

Before running eye_blink.py install pymouse and xlib then run eye_blink.py by adding the argument as the path to the facial landmark predictor. Also, set the threshold as you find suitable.

The facial landmark predictor in all the above cases is the shape_predictor_68_face_landmarks.dat file

---------------------------------