# IoT Security Framework for Smart Cities

This project presents a lightweight and scalable security framework designed to protect IoT devices in smart city environments. It focuses on low-resource devices and aims to achieve strong encryption, device authentication, intrusion detection, and data privacy — all while maintaining efficiency and compliance with global standards.

## 🔐 Key Features

- **TLS 1.3 Encryption** for secure MQTT communication
- **ECDSA Certificates** for lightweight device authentication
- **Suricata IDS** with customized rules for detecting MQTT-based threats
- **K-Anonymity Engine** to ensure GDPR-compliant data privacy
- **Low-resource design** optimized for 500+ concurrent devices

## 🧰 Tools & Technologies

- **Mosquitto MQTT Broker** (v2.0.18)
- **Suricata IDS** (Custom rules for MQTT)
- **OpenSSL** (Certificate generation and validation)
- **Python + Flask** (Dashboard prototype)
- **Jupyter Notebook** (Analysis & testing)
- **mqtt-bench** (Device simulation)
- **TLS 1.3**, **ECDSA**, **AES-256-GCM**, **JSON**, **X.509**

## 🏗️ System Architecture

Three-layer architecture:
1. **Device Layer**: Sensors (temperature, humidity, etc.)
2. **Network Layer**: Mosquitto + TLS 1.3 encryption
3. **Threat Layer**: Suricata IDS + Anonymization Engine

## 📊 Testing & Results

- Simulated 500+ devices with 1000 msg/sec
- Achieved **100% attack detection rate**
- Reduced false positives from 40% to **1.6%**
- Maintained CPU usage under **32.7%**
- Maintained latency below **383ms** (99th percentile)

## 📌 Why This Project Matters

- Fills the gap between **theoretical models** and **real-world constraints**
- Provides **affordable**, **open-source**, and **compliant** security architecture
- Supports **Vision 2030** and smart city initiatives like **NEOM** in Saudi Arabia

## 🚫 Excluded from Scope

- **Cameras and video surveillance**: Intentionally excluded to reduce resource demands and cost, focusing instead on low-power sensors and lightweight protocols.

