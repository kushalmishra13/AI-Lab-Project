# ALPHA | Real-Time Sign Language Neural Translation Engine 🤟⚡

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
- **[TensorFlow.js](https://www.tensorflow.org/js):** Client-side machine learning computation.
- **[MobileNet](https://github.com/tensorflow/tfjs-models/tree/master/mobilenet):** Pre-trained CNN model for extracting high-level feature vectors.
- **[KNN Classifier](https://github.com/tensorflow/tfjs-models/tree/master/knn-classifier):** Instant transfer learning for customized sign dataset registration.

### **Frontend & Interface**
- **HTML5 & Modern JavaScript (ES6+)**
- **[Tailwind CSS](https://tailwindcss.com/):** Dynamic, utility-first styling with dark mode themes.

### **APIs & Hardware Access**
- **Media Capture and Streams API (`getUserMedia`):** Low-latency webcam stream capture.
- **Web Speech Synthesis API:** Native voice synthesizer for real-time text-to-speech output.
- **Web Storage API (`localStorage`):** Persistent dataset state management.

---

## 🚀 Getting Started

No heavy installation or backend configuration is required! ALPHA runs directly inside any modern web browser.

### **1. Clone the Repository**
```bash
git clone [https://github.com/your-username/alpha-sign-language.git](https://github.com/your-username/alpha-sign-language.git)
cd alpha-sign-language

2. Launch the Application
Open index.html directly in your favorite browser (Chrome, Edge, or Safari recommended), or use Live Server in VS Code:

# Optional local server execution
python -m http.server 8000

Navigate to http://localhost:8000 in your web browser.

📖 How to Use
Select Input Source: Choose between Webcam Feed or File Upload (Images/Videos).

Register Samples:

Enter a gesture name (or use existing defaults like Hello, Need Water, Thank You).

Show the gesture to the camera/image and click the Register Sample button multiple times for higher accuracy.

Run Predictions:

Click Run Single Prediction or toggle Live Stream Mode for continuous real-time translation.

Voice Synthesizer: Ensure Voice Synthesizer is enabled to hear instant spoken translation.

Save & Export: Click Save Model to Storage to retain training locally, or Export JSON File to share the trained model dataset.

🙏 Acknowledgment
We express our sincere gratitude and deep appreciation to our faculty mentor and project guide, Ms. Anjali Srivastava, for her valuable guidance, constant encouragement, and insightful feedback throughout the conceptualization and development of ALPHA. Her technical mentorship and support were instrumental in successfully realizing this project.

We also acknowledge the open-source machine learning community and the creators of TensorFlow.js and MobileNet for providing the foundational infrastructure that made real-time client-side inferencing possible.

👨‍💻 Team Alpha & Contributions
This project was engineered collaboratively as a joint effort:

Abhinav — Backend & AI Integration Lead

Architected Machine Learning pipelines (TensorFlow.js & KNN Classifier).

Implemented client-side state management, LocalStorage data persistence, and JSON Export/Import capabilities.

Handled Media Capture APIs and Web Speech Synthesis logic.

Kushal — Frontend & UI/UX Developer

Designed and developed the user interface using HTML5 & Tailwind CSS.

Built the responsive dashboard layout, glassmorphism design system, and real-time visual telemetry feedback widgets.

Managed UI states, interaction controls, and user experience flows.

📄 License
This project is open-source and available under the MIT License.

