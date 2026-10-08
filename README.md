# ALPHA | Real-Time Sign Language Neural Translation Engine 🤟⚡

**Course:** AI Lab Project  
**Under the Mentorship of:** Ms. Anjali Srivastava  

---

## 👨‍💻 Student Contributors & Project Work

- **Abhinav** — *Backend & AI Integration Lead*
  - Architected Machine Learning pipelines (TensorFlow.js & KNN Classifier).
  - Implemented client-side state management, LocalStorage data persistence, and JSON Export/Import capabilities.
  - Handled Media Capture APIs and Web Speech Synthesis logic.

- **Kushal** — *Frontend & UI/UX Developer*
  - Designed and developed the user interface using HTML5 & Tailwind CSS.
  - Built the responsive dashboard layout, glassmorphism design system, and real-time visual telemetry feedback widgets.
  - Managed UI states, interaction controls, and user experience flows.

---

## 📌 Project Overview

ALPHA is an enterprise-grade, browser-based computer vision application designed to translate sign language gestures into text and audible speech in real time. Built using Client-Side Artificial Intelligence and Transfer Learning, ALPHA enables seamless communication without relying on external server latency or cloud API costs.

---

## 🌟 Key Features

- **Real-Time Gesture Recognition:** Client-side inferencing using MobileNet feature extraction and KNN classification.
- **Text-to-Speech (TTS) Integration:** Integrated Web Speech API converts recognized sign gestures into clear verbal audio output.
- **Browser-Side Persistence:** Automatically saves trained weights and dataset configurations directly to `localStorage`.
- **Flexible Data Controls:** Export trained datasets as custom `.json` files and import them across sessions or devices.
- **Multi-Source Support:** Works seamlessly with Live Webcam Streams, static Images, and Video files.
- **Enterprise UI Dashboard:** Modern, glassmorphism-inspired dark UI built with Tailwind CSS.

---

## 🛠️ Tech Stack & Architecture

### **AI & Machine Learning**
- **TensorFlow.js:** Client-side machine learning computation.
- **MobileNet:** Pre-trained CNN model for extracting high-level feature vectors.
- **KNN Classifier:** Instant transfer learning for customized sign dataset registration.

### **Frontend & Interface**
- **HTML5 & Modern JavaScript (ES6+)**
- **Tailwind CSS:** Dynamic, utility-first styling with dark mode themes.

### **APIs & Hardware Access**
- **Media Capture and Streams API (`getUserMedia`):** Low-latency webcam stream capture.
- **Web Speech Synthesis API:** Native voice synthesizer for real-time text-to-speech output.
- **Web Storage API (`localStorage`):** Persistent dataset state management.

---

## 🚀 Getting Started

No heavy installation or backend configuration is required! ALPHA runs directly inside any modern web browser.

### **1. Clone the Repository**
```bash
git clone [https://github.com/kushalmishra13/AI-Lab-Project.git](https://github.com/kushalmishra13/AI-Lab-Project.git)
cd AI-Lab-Project
