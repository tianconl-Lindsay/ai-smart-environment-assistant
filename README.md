# 🤖 AI-Powered Smart Environment Assistant

An **embedded AI IoT system** integrating **ESP32 sensor nodes**, **Raspberry Pi edge gateway**, and a **camera** for intelligent environmental monitoring and **voice-based device control**.

---

## 🧩 System Overview

The system combines multiple microcontrollers and AI components:

| Component | Function |
|------------|-----------|
| **ESP32 Nodes** | Measure temperature, light, humidity, and control fan/light actuators |
| **Raspberry Pi** | Runs AI models, MQTT broker, and Node-RED dashboard |
| **Camera** | Enables vision-based scene detection (e.g., human presence) |
| **Speaker & Mic** | Used for voice commands via offline recognition (TensorFlow Lite + Vosk) |

---

## ⚙️ Architecture

