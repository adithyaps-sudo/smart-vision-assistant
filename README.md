# 🤖  Smart Vision Assistant

An intelligent real-time Smart Vision Assistant developed using Computer Vision, Hand Gesture Recognition, Object Detection, and Large Language Model (LLM) integration. The system allows users to interact with detected objects using hand gestures and receive AI-generated responses through voice/text interaction.

---

# 📌 Features

- Real-time Object Detection using YOLOv8
- Hand Gesture Recognition using MediaPipe
- Gesture-based Object Selection
- Virtual Pointer Control
- AI-powered Question Answering using Groq LLM
- Interactive User Interface with Live Camera Feed
- Smart Human-Computer Interaction System

---

# 🛠 Technologies Used

- Python
- OpenCV
- MediaPipe
- YOLOv8
- NumPy
- Groq API / LLM
- Computer Vision
- Artificial Intelligence

---

# ⚙️ Working Principle

1. Captures live video using webcam.
2. Detects objects in real time using YOLOv8.
3. Tracks hand landmarks using MediaPipe.
4. Uses finger gestures for virtual pointer control.
5. Allows users to select objects using 2-finger gesture.
6. Sends user questions to Groq LLM API.
7. Generates intelligent AI responses related to selected objects.

---

# 📂 Project Structure

```plaintext
Smart-Vision-Assistant/
│
├── main.py
├── yolov8n.pt
├── hand_landmarker.task
├── requirements.txt
└── README.md
````

---

# ▶️ Installation

## Clone Repository

```bash
git clone <your-github-repo-link>
cd Smart-Vision-Assistant
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 📦 Required Libraries

```bash
pip install opencv-python mediapipe ultralytics numpy openai
```

---

# ▶️ Run the Project

```bash
python main.py
```

---

# 🎮 Controls

| Gesture / Key | Function        |
| ------------- | --------------- |
| 2 Fingers     | Select Object   |
| Q Key         | Ask AI Question |
| ESC Key       | Exit Program    |

---

# 📌 Note

Ensure that:

* `yolov8n.pt`
* `hand_landmarker.task`

are placed correctly in the project directory before running the program.

---

# 🚀 Future Improvements

* Voice Assistant Integration
* Text-to-Speech Response
* Multiple Hand Gesture Controls
* Smart Home Automation Integration
* Mobile/Embedded Deployment

---

# 👨‍💻 Developed By

Adithya P S
Robotics & Automation Engineering

---

# ⭐ Support

If you found this project useful, consider giving this repository a ⭐ on GitHub!

```
```
