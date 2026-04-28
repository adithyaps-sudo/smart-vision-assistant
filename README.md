👁️ **Gesture-Based Smart Vision Assistant using YOLO & LLM**
An AI-powered real-time vision assistant that combines object detection, hand gesture interaction, and Large Language Models (LLMs) to enable a completely touchless human-computer interaction system.
Users can point at objects using hand gestures, select them, and ask questions to receive intelligent, context-aware responses.

🚀 **Features**
👁️** Real-Time Object Detection**


Powered by YOLOv8


Detects multiple objects in real-time


Filters unnecessary classes (e.g., person)


✋** Gesture-Based Interaction**


Built using MediaPipe Hand Landmarker


Finger-based control:


👆 1 Finger → Pointer movement


✌️ 2 Fingers → Select object (hold gesture)




🎯 **Smart Object Selection**


Pointer tracks index finger


Hover detection inside bounding box


Hold gesture (1 sec) for confirmation


🧠 **AI Question Answering**


Integrated with LLaMA 3 (via Groq API)


Ask questions about selected objects


Provides intelligent, contextual answers


🖥️ **Interactive UI**


Bounding boxes with labels


Hover highlight effect


Smooth pointer movement


Real-time feedback display



🧠 **How It Works**


Webcam captures live video feed


YOLOv8 detects objects in the frame


MediaPipe tracks hand landmarks (21 key points)


Finger positions determine gesture


Index finger controls on-screen pointer


Pointer hovering inside object → detection


Hold ✌️ gesture → object selection


Press Q to ask a question


LLM generates an intelligent response



🏗️ **System Architecture**
Camera Input
     ↓
YOLOv8 → Object Detection
     ↓
MediaPipe → Hand Tracking
     ↓
Gesture Logic → Pointer Control
     ↓
Object Selection
     ↓
LLM (Groq API - LLaMA 3)
     ↓
Answer Output


🛠️ **Technologies Used**


Python


OpenCV – Video processing & UI rendering


MediaPipe – Hand gesture tracking


YOLOv8 (Ultralytics) – Object detection


NumPy – Numerical operations


Groq API (LLaMA 3) – AI responses



📦 **Requirements**
Install all dependencies:
pip install opencv-python mediapipe numpy ultralytics openai


⚙️ **Setup & Installation**
1️⃣ **Clone the repository**
git clone https://github.com/your-username/gesture-vision-assistant.git
cd gesture-vision-assistant

2️⃣ **Add required model files**
Make sure these files are in your project folder:


yolov8n.pt


hand_landmarker.task


3️⃣ **Add your API key**
Replace this in the code:
api_key="your_api_key_here"


4️⃣ **Run the project**
python main.py


🎮 **How to Use**


Launch the program


Show your hand to the camera


Move pointer using index finger


Hover over an object


Hold ✌️ gesture for 1 second to select


Press Q


Ask your question in terminal


Get AI-generated answer


🏆 **Key Highlights**


Developed a multimodal AI system (Vision + Gesture + LLM)


Implemented real-time object interaction


Enabled touchless control using hand gestures


Integrated AI-based contextual question answering



🌍 **Applications**


Smart assistants


Interactive kiosks


Accessibility tools


AI-based education systems


Human-computer interaction research



🚧 **Future Improvements**


🎤 Voice-based input


📱 Mobile or web integration


🌐 Multi-language support


🤖 Advanced gesture recognition



👤**Author**
P.S Adithya
📍 Kerala, India

⚠️ Notes


Ensure model files are correctly placed


Webcam access is required


Internet connection needed for LLM



⭐ **Support**
If you found this project useful, consider giving it a ⭐ on GitHub!
