# ALPHA | Real-Time Sign Language Neural Translation Engine 🤟⚡

**Course:** AI Lab Project  
**Mentored By:** Ms. Anjali Srivastava  

---

## 👨‍💻 Student Contributors & Division of Labor

- **Abhinav** — *Backend & AI Integration Lead*
  - Architected Machine Learning pipelines using TensorFlow.js & KNN Classifier.
  - Implemented client-side state management, LocalStorage data persistence, and JSON Export/Import capabilities.
  - Integrated Media Capture APIs and Web Speech Synthesis logic.

- **Kushal** — *Frontend & UI/UX Developer*
  - Designed and built the user interface using HTML5 & Tailwind CSS.
  - Developed the responsive dashboard layout, glassmorphism design system, and real-time visual feedback controls.
  - Managed UI interaction flows and state handling.

---

## 📌 Project Overview

ALPHA is an enterprise-grade, browser-based computer vision application designed to translate sign language gestures into text and audible speech in real time. Built using Client-Side Artificial Intelligence and Transfer Learning, ALPHA enables seamless communication without relying on external server latency or cloud API costs.

---

## 🔄 System Architecture & Workflow

1. **Video/Image Stream Ingestion:** Media Devices API captures low-latency frames from live webcam streams or uploaded media files.
2. **Feature Extraction:** TensorFlow.js feeds raw image frames into a pre-trained **MobileNet** CNN model to extract high-level feature tensors.
3. **Transfer Learning Classification:** Extracted feature vectors are registered into a **K-Nearest Neighbors (KNN) Classifier** to train and identify custom gesture classes instantly.
4. **Speech & Persistence Pipeline:** Recognized gestures generate real-time visual output, trigger native spoken audio via the **Web Speech API**, and automatically synchronize dataset weights to **LocalStorage** or export them as JSON files.

---

## 🛠️ Tech Stack, Tools & Technologies

### **AI & Machine Learning Frameworks**
- **TensorFlow.js:** In-browser machine learning execution engine.
- **MobileNet:** Lightweight Deep Learning Convolutional Neural Network (CNN) for feature extraction.
- **KNN Classifier:** Instant transfer-learning model for real-time sign sample registration and matching.

### **Frontend & Interface Stack**
- **HTML5 & Modern JavaScript (ES6+):** Core application markup and asynchronous event logic.
- **Tailwind CSS:** Utility-first CSS framework for modern dark-mode glassmorphism styling.
- **VS Code:** Primary Integrated Development Environment (IDE).

### **Browser APIs & Hardware Integration**
- **Media Capture and Streams API (`getUserMedia`):** Direct hardware access for low-latency webcam streaming.
- **Web Speech Synthesis API:** Native browser speech engine converting recognized sign text to audio output.
- **Web Storage API (`localStorage`):** Persistent client-side data state management.

---

## 🌟 Key Features

- **Real-Time Gesture Recognition:** Client-side inferencing using MobileNet feature extraction and KNN classification.
- **Text-to-Speech (TTS) Integration:** Integrated Web Speech API converts recognized sign gestures into clear verbal audio output.
- **Browser-Side Persistence:** Automatically saves trained weights and dataset configurations directly to `localStorage`.
- **Flexible Data Controls:** Export trained datasets as custom `.json` files and import them across sessions or devices.
- **Multi-Source Support:** Works seamlessly with Live Webcam Streams, static Images, and Video files.
- **Enterprise UI Dashboard:** Modern, glassmorphism-inspired dark UI built with Tailwind CSS.

---

## 🚀 Getting Started

No heavy installation or backend configuration is required! ALPHA runs directly inside any modern web browser.

### **1. Clone the Repository**

`git clone https://github.com/kushalmishra13/AI-Lab-Project.git`  
`cd AI-Lab-Project`

### **2. Launch the Application**

Open `index.html` directly in your favorite browser (Chrome, Edge, or Safari recommended), or use Live Server in VS Code:

`python -m http.server 8000`

Navigate to `http://localhost:8000` in your web browser.

---
## 🔄 System Architecture & Workflow

1. **Video/Image Stream Ingestion:** Media Devices API captures low-latency frames from live webcam streams or uploaded media files.
2. **Feature Extraction:** TensorFlow.js feeds raw image frames into a pre-trained **MobileNet** CNN model to extract high-level feature tensors.
3. **Transfer Learning Classification:** Extracted feature vectors are registered into a **K-Nearest Neighbors (KNN) Classifier** to train and identify custom gesture classes instantly.
4. **Speech & Persistence Pipeline:** Recognized gestures generate real-time visual output, trigger native spoken audio via the **Web Speech API**, and automatically synchronize dataset weights to **LocalStorage** or export them as JSON files.

---

## 🛠️ Tech Stack, Tools & Technologies

### **AI & Machine Learning Frameworks**
- **TensorFlow.js:** In-browser machine learning execution engine.
- **MobileNet:** Lightweight Deep Learning Convolutional Neural Network (CNN) for feature extraction.
- **KNN Classifier:** Instant transfer-learning model for real-time sign sample registration and matching.

### **Frontend & Interface Stack**
- **HTML5 & Modern JavaScript (ES6+):** Core application markup and asynchronous event logic.
- **Tailwind CSS:** Utility-first CSS framework for modern dark-mode glassmorphism styling.
- **VS Code:** Primary Integrated Development Environment (IDE).

### **Browser APIs & Hardware Integration**
- **Media Capture and Streams API (`getUserMedia`):** Direct hardware access for low-latency webcam streaming.
- **Web Speech Synthesis API:** Native browser speech engine converting recognized sign text to audio output.
- **Web Storage API (`localStorage`):** Persistent client-side data state management.
## 📖 How to Use

1. **Select Input Source:** Choose between **Webcam Feed** or **File Upload** (Images/Videos).
2. **Register Samples:**
   - Enter a gesture name (or use existing defaults like *Hello*, *Need Water*, *Thank You*).
   - Show the gesture to the camera/image and click the **Register Sample** button multiple times for higher accuracy.
3. **Run Predictions:**
   - Click **Run Single Prediction** or toggle **Live Stream Mode** for continuous real-time translation.
4. **Voice Synthesizer:** Ensure **Voice Synthesizer** is enabled to hear instant spoken translation.
5. **Save & Export:** Click **Save Model to Storage** to retain training locally, or **Export JSON File** to share the trained model dataset.

---

## 🙏 Acknowledgment

We express our sincere gratitude and deep appreciation to our faculty mentor and project guide, **Ms. Anjali Srivastava**, for her valuable guidance, constant encouragement, and insightful feedback throughout the conceptualization and development of **ALPHA**. Her technical mentorship and support were instrumental in successfully realizing this project as part of our **AI Lab**.

We also acknowledge the open-source machine learning community and the creators of **TensorFlow.js** and **MobileNet** for providing the foundational infrastructure that made real-time client-side inferencing possible.
