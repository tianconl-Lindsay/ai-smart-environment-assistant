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

[ESP32 Sensors/Actuators] ⇄ MQTT ⇄ [Raspberry Pi Edge Server]
│
├── AI Inference (Camera + Voice)
├── Node-RED Dashboard
└── Cloud Sync (optional)

---

## 🧠 Key Features
- Real-time sensor acquisition via **FreeRTOS tasks**  
- Edge AI inference using **TensorFlow Lite**  
- **Voice-controlled automation** (e.g., “turn on fan”)  
- **MQTT-based communication** between ESP32 & Raspberry Pi  
- **Node-RED dashboard** for visualization and remote control  

---

## 🛠️ Hardware Used
- Raspberry Pi 4 B (or 5)  
- ESP32 DevKit C  
- DHT11 / LM35 temperature sensor  
- Light sensor (LDR)  
- Relay / Transistor for fan and light control  
- USB Camera  
- Speaker + Microphone  

---

## 💻 Software Stack
| Layer | Technology |
|-------|-------------|
| Embedded | C / FreeRTOS on ESP32 |
| Edge | Python 3 on Raspberry Pi |
| AI | TensorFlow Lite, Vosk Speech Recognition |
| Communication | MQTT (Mosquitto Broker) |
| Visualization | Node-RED Dashboard |

---

## 🚀 Getting Started
1. **Clone repository**
   ```bash
   git clone https://github.com/tianconl-lindsay/ai-smart-environment-assistant.git
   cd ai-smart-environment-assistant
