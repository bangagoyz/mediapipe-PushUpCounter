# Push-Up Counter Using MediaPipe Pose Estimation

This project uses **MediaPipe Pose** (via a custom `PoseModule.py`) and **OpenCV** to automatically count push-ups from a video or webcam feed. The system tracks elbow angles, determines movement stages (UP/DOWN), and increments the push-up count in real time.

---

## 📌 Features

- Real-time pose detection using MediaPipe  
- Elbow angle tracking for detecting push-up motion  
- Automatic and accurate push-up counter  
- Dynamic progress bar (0%–100%)  
- Movement stage detection (**UP** / **DOWN**)  
- FPS monitoring  
- Works with both video files and webcam  

---

## 🛠 Installation

Install the required libraries:

```bash
pip install opencv-python mediapipe numpy

````
![Image](https://github.com/user-attachments/assets/b4a9a82a-83c4-4e96-a907-4a8fb6836536)
