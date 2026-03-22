🚀 TransMonitor – Smart Transformer Monitoring System

IoT-based transformer health monitoring system with real-time sensor data, alerting, and predictive analytics.

📌 Overview

TransMonitor is a full-stack IoT solution designed to monitor the health of electrical transformers using real-time sensor data.
It integrates hardware (ESP32) with a web-based dashboard to provide live monitoring, alerts, and basic predictive maintenance insights.

🛠️ Tech Stack
Frontend: React.js
Backend: Flask (Python)
Database: SQLite / MySQL
Hardware: ESP32, Sensors (Temperature, Voltage, Current)
Machine Learning: Predictive maintenance (basic model using Scikit-learn / LSTM)
⚙️ Features
📡 Real-time data collection from ESP32 sensors
📊 Live dashboard for transformer parameters
🚨 Alert system for abnormal conditions
🔐 JWT-based authentication
📁 REST API for data handling
🤖 Basic predictive maintenance using ML models
🔄 Device simulation for testing without hardware
🏗️ Project Structure
TransMonitor/
│── backend/        # Flask backend (APIs, ML models)
│── frontend/       # React frontend (UI dashboard)
│── esp-device/     # ESP32 code (sensor integration)
│── README.md
│── .gitignore
🔌 Hardware Setup
ESP32 microcontroller collects:
Temperature
Voltage
Current
Sends data to backend via HTTP API
🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/Auro993/TransMonitor.git
cd TransMonitor
2️⃣ Backend Setup
cd backend
pip install -r requirements.txt
python app.py
3️⃣ Frontend Setup
cd frontend
npm install
npm start
4️⃣ ESP32 Setup
Open esp-device in PlatformIO / Arduino IDE
Upload code to ESP32
Configure WiFi & API endpoint
📊 Machine Learning (Basic)
Uses historical sensor data
Models included:
Regression / classification models
Optional LSTM model for prediction
Helps detect potential failures early
📸 Screenshots

(Add your UI screenshots here for better presentation)

🔒 Security Note
.env files are excluded for security
Use your own environment variables for API keys and DB config
🎯 Future Improvements
Advanced ML models for better prediction
Cloud deployment (AWS / Azure)
Mobile app integration
Real-time notifications (SMS/Email)
👨‍💻 Author

Aurosmita Sahoo
Final Year Student | Full Stack Developer | IoT Enthusiast

📎 Project Link

👉 https://github.com/Auro993/TransMonitor
