# Assistive AI Indoor NeuraLens (Online Mode)

![alt text](https://img.shields.io/badge/license-MIT-blue.svg)
![alt text](https://img.shields.io/badge/python-3.8%2B-green.svg)
![alt text](https://img.shields.io/badge/status-active-orange.svg)

Assistive AI Indoor NeuraLens is a module of the NeuraLens ecosystem designed to provide real-time visual assistance for the visually impaired in indoor environments. The Online Mode leverages cloud-based APIs and high-performance neural networks to provide superior accuracy in object recognition, scene description, and pathfinding.

## 🚀 Overview
While Offline Mode focuses on speed and low latency, the Online Mode is designed for deep contextual understanding. It uses internet connectivity to access powerful Vision-Language Models (VLMs) and Cloud APIs to help users navigate complex indoor layouts (like malls, offices, or transit hubs).

## ✨ Key Features
* **Contextual Scene Description:** Goes beyond simple object naming to describe the relationship between objects (e.g., "A wooden chair is 2 meters ahead to your left").
* **Dynamic Navigation:** Real-time pathfinding assistance to avoid obstacles and find specific indoor landmarks (doors, elevators, restrooms).
* **Cloud-Enhanced Accuracy:** Uses high-parameter models for precise identification of household items, text on signage, and facial recognition.
* **Voice-First Interface:** Integrated text-to-speech (TTS) to provide natural, conversational guidance to the user.
* **Low Latency Streaming:** Optimized data transmission to ensure the cloud-processed feedback reaches the user in near real-time.

## 🛠 Tech Stack
* **Language:** Python
* **Computer Vision:** OpenCV, Mediapipe
* **AI/ML Frameworks:** TensorFlow/PyTorch
* **Cloud Integration:** (e.g., OpenAI GPT-4o Vision, Google Gemini Vision, or AWS Rekognition)
* **Communication:** WebSockets / MQTT for real-time data flow
* **Speech Engine:** gTTS (Google Text-to-Speech) or pyttsx3

## 📦 Installation
1. **Clone the repository:**
```bash
git clone https://github.com/Subash-Poudel1059/Assistive_AI_Indoor_NeuraLens_OnlineMode
cd Assistive_AI_Indoor_NeuraLens_OnlineMode