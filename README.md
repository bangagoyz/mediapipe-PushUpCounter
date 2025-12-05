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

![pushup320](https://github.com/user-attachments/assets/15d1f6e8-0d59-48b3-84a5-5b994848d785)
