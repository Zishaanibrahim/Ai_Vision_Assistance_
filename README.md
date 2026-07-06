# AI-Based Vision Assistance System

An AI-powered, real-time vision assistance application for visually impaired users. It uses computer vision to detect objects and read printed text through a webcam, then delivers instant audio feedback — no specialized hardware required.

---

##  Description

This project bridges the gap between visual impairment and independence by leveraging modern AI and computer vision. Using just a laptop webcam, the system continuously analyzes the environment, identifies objects, and reads text aloud — making everyday interactions more accessible.

---

##  Features

-  **Real-time Object Detection** — Identifies surrounding objects using ML-based computer vision
-  **Audio Feedback** — Converts visual information into spoken output instantly
-  **OCR / Text Reading** — Reads printed text from signs, books, and documents
-  **No Special Hardware Needed** — Works with any standard laptop webcam and speaker
-  **Web Interface** — Accessible via browser at `localhost:5173`

---

##  Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Computer Vision | OpenCV |
| AI / ML Framework | TensorFlow / PyTorch |
| OCR | Tesseract OCR / EasyOCR |
| Text-to-Speech | pyttsx3 / gTTS |
| Dev Environment | VS Code / PyCharm + Anaconda |
| Supported OS | Windows / Linux / macOS |

---

##  Requirements

### Hardware
- Processor: Intel Core i5 or higher
- RAM: 4 GB minimum
- Storage: 100 GB HDD/SSD
- Webcam + Speaker
- Internet connection (for initial setup)

### Software
- Python (via Anaconda)
- OpenCV
- TensorFlow or PyTorch
- Tesseract OCR
- pyttsx3 / gTTS

---

##  Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/ai-vision-assistance.git
cd ai-vision-assistance
```

### 2. Set up the Python environment (Anaconda recommended)
```bash
conda create -n vision-assist python=3.9
conda activate vision-assist
pip install -r requirements.txt
```

### 3. Install Tesseract OCR
- **Windows:** Download from [tesseract-ocr](https://github.com/tesseract-ocr/tesseract)
- **Linux:** `sudo apt install tesseract-ocr`
- **macOS:** `brew install tesseract`

### 4. Launch the application
```bash
./start.sh
```

### 5. Open in browser
```
http://localhost:5173
```

The system will initialize your webcam and begin the AI detection loop automatically.

---

##  Project Structure

```
ai-vision-assistance/
├── start.sh               # Launch script
├── requirements.txt       # Python dependencies
├── src/
│   ├── detection/         # Object detection module
│   ├── ocr/               # Text recognition module
│   └── tts/               # Text-to-speech module
├── models/                # Pre-trained ML models
└── README.md
```

---

##  Use Cases

- Identifying objects and obstacles in the environment
- Reading labels, signs, and printed documents
- Providing real-time situational awareness for visually impaired individuals

---
