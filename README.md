# 🧠 AI Full-Stack Finger-Tip Scanner Web App

A full-stack web application that uses AI to scan your finger tips (or gestures) and perform operations based on them.

---

## 📋 Table of Contents

- [About](#about)  
- [Features](#features)  
- [Architecture](#architecture)  
- [Tech Stack](#tech-stack)  
- [Setup & Installation](#setup--installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)

---

## 🧾 About

This project is a **full-stack AI-powered web application** built to detect finger-tip movements or hand gestures using computer vision.  
It demonstrates real-time AI inference on a web interface, enabling gesture-based control and interaction.

---

## ✨ Features

- 🎥 Real-time finger-tip or gesture detection  
- 🧠 AI / Computer Vision integration for gesture recognition  
- 💻 Web interface with live camera feed  
- ⚡ Instant response to gestures (e.g., perform custom actions)  
- 📁 Image upload support for offline AI processing  

---

## 🏗 Architecture

The project follows a **client-server architecture**:

1. **Frontend (Client)**  
   - Captures webcam input using JavaScript  
   - Displays video feed and gesture results  
   - Sends data (frames or images) to backend  

2. **Backend (Server)**  
   - Built in Python (Flask or FastAPI)  
   - Processes frames with AI / CV libraries (e.g., OpenCV, Mediapipe)  
   - Returns gesture predictions to the frontend  

3. **AI Model**  
   - A pre-trained or custom ML model for recognizing finger-tip positions or hand gestures  

4. **Output**  
   - The detected gestures trigger corresponding operations or UI updates in real-time.  

---

## 🧰 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Python (Flask / FastAPI) |
| **AI / CV** | OpenCV, Mediapipe, TensorFlow / PyTorch |
| **Tools** | VS Code, Git, Browser APIs |
| **Version Control** | Git & GitHub |

---

## ⚙️ Setup & Installation

Follow these steps to run the project locally:

### 1. Clone the repository
```bash
git clone https://github.com/Suru12415/Ai-full-stack-project.git
cd Ai-full-stack-project
```
2. Set up a Python virtual environment
```bash
install python 3.10 from 
https://www.python.org/downloads/source/
python3 -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
```
3. Install dependencies
```bash
pip install -r requirements.txt
```
4. Run the backend server
```bash
python upload.py
```
5. Open the web app
```bash
(http://localhost:5000)
```

## 🚀 Usage

1. Allow webcam access when prompted.  
2. Show your fingers or gestures in front of the camera.  
3. The AI model detects finger-tips or gestures in real-time.  
4. Detected gestures trigger predefined operations or UI actions.  
5. (Optional) Upload an image for gesture recognition without using the camera.  

---

## 📁 Project Structure
```
|Ai-full-stack-project/ 
├── mobile.html # Main web UI page 
├── mobile-web-video-playback.js # Frontend logic for video handling 
├── mobile-web-video-playback.css # Stylesheet for UI 
├── upload.py # Backend Python server 
├── requirements.txt # Dependencies file and
└── (AI / Model files) # AI model scripts, weights, or utils v
```
---

## 🤝 Contributing

Contributions are always welcome!  

### Steps:
1. **Fork** the repository  
2. **Create a feature branch:**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3.**Commit your changes:**
  ```bash
  git commit -m "Add: your feature"
   ```
4.**Push to your branch and create a Pull Request**



### Please make sure to:
- Follow the existing code style  
- Add meaningful commit messages  
- Test your code before submission  

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more details.

---

## 📞 Contact

**Author:** Suru12415  
**GitHub:** [Suru12415](https://github.com/Suru12415)  
**Email:** *try.sureshtak@gmail.com*  


