# identifying-left-right-hand-using-python using OpenCV and cvzone

This Python project detects a hand in real time using your webcam and displays the number of hand landmarks detected. It uses **OpenCV** for video capture and **cvzone** (which internally uses **MediaPipe**) for hand tracking.

---

## 📸 Features
- Detects a hand in real time using your webcam  
- Displays the video feed with hand landmark points  
- Prints the number of landmarks detected in the console  
- Press **‘q’** to quit the window

---

## 🧰 Requirements

Make sure you have Python 3.8 or higher installed, then install the required packages:

```bash
pip install opencv-python cvzone mediapipe

🧠 How It Works
cv2.VideoCapture(0) opens the default webcam
HandDetector (from cvzone.HandTrackingModule) detects the hand in the camera feed
The program retrieves the list of hand landmarks using lmList
The number of landmarks is printed to the console
OpenCV (cv2.imshow) displays the live video feed with the detected hand

🧾 Example Output

Console:

no of landmarks: 21
