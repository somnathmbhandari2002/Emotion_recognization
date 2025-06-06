# Emotion_recognization
This code uses FER and OpenCV to detect emotions in real-time from a webcam feed, printing the detected emotions and displaying the video stream until the user presses 'q'.

Emotion Detection using FER and OpenCV
Overview
This code uses the FER (Facial Emotion Recognition) library and OpenCV to detect emotions in real-time from a webcam feed. The detected emotions are printed to the console, and the video stream is displayed on the screen.
Requirements
Python 3.x
FER library (pip install fer)
OpenCV library (pip install opencv-python)
MoviePy library (pip install moviepy)
Usage
Install the required libraries using pip.
Run the code using Python (e.g., python emotion_detection.py).
The code will start capturing video from the default webcam and detecting emotions in real-time.
Press 'q' to quit the program.
How it Works
The code initializes the FER detector with the MTCNN face detector.
It captures video frames from the webcam using OpenCV.
For each frame, it detects faces and recognizes emotions using the FER detector.
The detected emotions are printed to the console.
The video stream is displayed on the screen using OpenCV.
Notes
This code uses the default webcam (index 0). If you have multiple webcams, you may need to change the index.
The FER library uses a pre-trained model for emotion recognition. You can fine-tune the model or use a different model if needed.
License
This code is released under the MIT License. Feel free to modify and use it as you see fit.

# Images
1 Happy
![image](https://github.com/user-attachments/assets/da18ea64-7d6d-45b0-a27a-df9d6621d8e1)

2 Angry
![image](https://github.com/user-attachments/assets/688f4edc-7c85-46b7-ba26-e232f1c6c673)

3 Fear
![image](https://github.com/user-attachments/assets/9bfacc98-287b-4c26-b74e-11a3222c869b)

4 Surprise
![image](https://github.com/user-attachments/assets/bf940474-1903-4c24-9d3e-e05c57b2dd02)
