👁️ Real-Time Face Detection Using OpenCV

This project is a simple real-time **face detection** application using **Python** and **OpenCV**. <br>It captures video from your webcam and uses a Haar Cascade classifier to detect faces, drawing green rectangles around them in the live feed.

📌 Features

- Live webcam video feed
- Real-time face detection using Haar Cascades
- Press `a` key to exit the video window

How It Works?
Loads a Haar Cascade XML file pre-trained for face detection.

Uses cv2.VideoCapture(0) to access your system's webcam.

Processes each frame in real time.

Converts each frame to grayscale for faster processing.

Uses detectMultiScale() to detect faces.

Draws rectangles over detected face regions.

