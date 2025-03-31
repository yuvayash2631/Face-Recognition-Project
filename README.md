
## Objective of the Face Recognition Project

- The objective of this project is to detect human faces in real-time using OpenCV and Haar Cascade Classifier. 
- By utilizing a webcam feed, the system continuously analyzes frames, detects faces, and highlights them with bounding boxes. 
- This project serves as a foundation for face recognition applications in security, attendance systems, and biometric authentication.


![Screenshot 2025-03-31 192922](https://github.com/user-attachments/assets/e0d16ce2-f45e-4ba1-b5eb-ff0a6bdeee49)



## Key Features:

- Real-time Face Detection – The system captures video frames and processes them to detect faces dynamically.
- Haar Cascade Classifier – A pre-trained XML model (haarcascade_frontalface_default.xml) is used for face detection.-✅ Grayscale Conversion – The video frames are converted to grayscale for faster and more efficient face detection.
- Bounding Box Display – Detected faces are highlighted with a green rectangle, making it easy to identify them.
- Continuous Frame Processing – The system runs in a loop until the user exits by pressing the ‘Esc’ key (27).
- Live Webcam Feed – Uses cv2.VideoCapture(0) to access the device’s webcam for real-time analysis.


## How It Works:

1.	The Haar Cascade face detection model is loaded.
2.	The webcam continuously captures live video frames.
3.	Each frame is converted to grayscale to improve detection speed.
4.	The classifier detects faces in the grayscale frame.
5.	A bounding box (rectangle) is drawn around each detected face.
6.	The video feed with detected faces is displayed in a window.
7.	The program runs in a loop until the user presses ‘Esc’ (27) to exit.


![Screenshot 2025-03-31 193028](https://github.com/user-attachments/assets/0bc451f4-e9fd-411f-b3ce-100f7a2c08f6)


## Conclusion:

- This project demonstrates a simple yet effective approach to real-time face detection using OpenCV. It serves as a building block for advanced face recognition systems in security, surveillance, attendance tracking, and biometric authentication applications. 

